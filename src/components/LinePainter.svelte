<script lang="ts">
    import Line from "./Line.svelte"
    import {randNumb} from "../utils/rand-numb";

    export let lineCount = 100;

    const maxHeight = 200;
    const minHeight = 30;
    const colors: string[] = [
        "green",
        "lightblue",
        "white",
        "orange",
        "yellow",
        "red",
        "lightgreen",
        "pink",
        "lightred"
    ];

    let innerHeight;
    let innerWidth;

    function randColor(colorList: string[]): string {
        return colorList[Math.floor(randNumb(0, colorList.length))];
    }

    function generateRandomLines(
        amount: number,
        colors: string[],
        minHeight: number,
        maxHeight: number,
        windowWidth: number,
        windowHeight: number
    ): {color: string, height: number, top: number, left: number}[] {
        return Array.from({length: amount}, (_) => ({
            color: randColor(colors),
            height: randNumb(minHeight, maxHeight),
            left: randNumb(0, windowWidth),
            top: randNumb(0, windowHeight)
        }));
    }

</script>

<svelte:window bind:innerHeight bind:innerWidth />

{#each generateRandomLines(
    lineCount,
    colors,
    minHeight,
    maxHeight,
    innerWidth,
    innerHeight
) as lineProps, i }
    <Line {...lineProps} index={i}/>
{/each}
