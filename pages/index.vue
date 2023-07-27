<template>
    <section>
        <Post />
        <Post />
        <Post />
        <Post />
    </section>
</template>

<style scoped>
@media (min-width: 765px) {
    section {
        overflow-y: scroll;
    }
}

section {
    display: flex;
    flex-direction: column;
    align-items: center;
    padding: 1rem 0.8rem 0 0.8rem;
}
</style>