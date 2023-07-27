<template>
    <article class="post">
        <div class="flex flex-col">
            <section class="flex justify-start items-center post-top">
                <div>img</div>
                <div class="grow">
                    <div class="flex flex-col">
                        <a href="#"><span>author name</span></a>
                        <a href="#">location</a>
                    </div>
                </div>
                <div class="flex-end">
                    <SVGMoreOptions />
                </div>
            </section>
        </div>
        <div class="post-container">
            <img class="post-content-size" src="assets/images/cat.jpg" alt="cat" srcset="">
        </div>
        <div>
            <div>
                <div>like</div>
                <div>comment</div>
                <div>share</div>
                <div>save</div>
            </div>
            <div>
                <div>user-photo</div>
                <p>like count</p>
            </div>
        </div>
        <p>
            author's description
        </p>
    </article>
</template>

<style scoped>
.post-container {
    margin: 0 0 1rem 0;
}

.post-content-size {
    object-fit: cover;
    width: 100%;
    border-radius: 3px;
}

.post-top {
    margin: 1.2rem 0.2rem
}

.post {
    max-width: 470px;
    padding-bottom: 2.5rem;
    border-bottom: 2px solid #e6e6e6;
}

.flex-col {
    flex-direction: column;
}

.flex {
    display: flex;
}

.grow {
    flex-grow: 1;
}

.justify-start {
    justify-content: flex-start;
    gap: 1rem;
}

.items-center {
    align-items: center;
}

.flex-end {
    justify-content: flex-end;
}
</style>