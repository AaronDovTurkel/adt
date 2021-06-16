<script lang="ts">
    export let color: string;
    export let height: number;
    export let top: number;
    export let left: number
    export let index: number;

</script>

<div style="
    --color: {color};
    --height: {height}px;
    --top: {top}px;
    --left: {left}px;
    --delay: {index + .3}s;
"></div>

<style>
    div {
        width: 5px;
        border-radius: 50px;
        position: absolute;
        background-color: var(--color);
        height: var(--height);
        top: calc(var(--top) - 300%);
        left: var(--left);
        animation: Rain 3s var(--delay) linear infinite;
        animation-fill-mode: forwards;
    }

    @keyframes Rain {
        0% {
            top: calc(var(--top) - 300%);

        }
        100% {
            top: calc(var(--top) + 100%);
        }
    }
</style>