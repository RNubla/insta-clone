<script lang="ts"></script>

<template>
    <main>
        <NavMenu />
        <slot />
    </main>
</template>

<style scoped>
main {
    display: grid;
    /* grid-template-columns: fit-content(5%) 1fr; */
    grid-template-rows: 1fr;
    gap: 0 5%;
    height: inherit;
    /* font-size: 6.4rem; */
}

@media (min-width: 600px) {
    main {
        grid-template-columns: 4.5rem 1fr;
    }
}

@media (min-width: 1250px) {
    main {
        grid-template-columns: 13% 1fr;
    }
}
</style>
