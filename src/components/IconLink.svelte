<script lang="ts">
    export let href: string;
</script>

<a {href}>
    <slot></slot>
</a>

<style>
    a {
        padding: 5px 10px;
        width: 40px;
        background-color: #262626;
        border-radius: 50px;
        z-index: 2;
    }

</style>