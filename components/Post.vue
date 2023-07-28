<template>
    <article class="post">
        <div class="flex flex-col">
            <section class="flex justify-start items-center post-top">
                <div class="profile-container">
                    <img class="profile-picture" src="assets/images/cat.jpg" alt="" srcset="">
                </div>
                <div class="grow">
                    <div class="flex flex-col author">
                        <a href="#"><span class="font-600">cutekitty</span></a>
                        <a class="location" href="#">New York, New York</a>
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
        <div class="px">
            <div class="flex actions">
                <div class="flex grow post-actions">
                    <button class="flex justiify-start items-center">
                        <SVGLike />
                    </button>
                    <button class="flex justify-start items-center">
                        <SVGComment />
                    </button>
                    <button class="flex justify-start items-center">
                        <SVGSharePost />
                    </button>
                </div>
                <div>
                    <SVGSave />
                </div>
            </div>
            <div class="likes">
                <p class="font-600">342 likes</p>
            </div>
        </div>
        <div class="px">
            <p>
                <a href="#"><span class="font-600">
                        cutekitty
                    </span>
                </a>
                Lorem, ipsum dolor sit amet consectetur adipisicing elit. Laudantium omnis quasi vel nisi possimus tenetur.
            </p>
        </div>
    </article>
</template>

<style scoped>
a:link,
a:visited,
a:hover,
a:active {
    text-decoration: none;
    color: black;
}

.px {
    padding: 0 1rem;
}

.font-600 {
    font-weight: 600;
}

.likes {
    margin-bottom: 1rem;
}

.actions {
    margin: 1rem 0;
}

.author {
    gap: 0.4rem;
}

.grow {
    flex-grow: 1;
}

.post-actions {
    gap: 1rem;
}

.post-actions button,
.post-actions button:focus {
    outline: none;
    background: transparent;
    border: none;
}

.location {
    font-size: 0.7rem
}

.profile-picture {
    object-fit: cover;
    width: 100%;
    border: 2px solid #e6e6e6;
    border-radius: 50%;
    max-width: 2.7rem;

}

.profile-container {}

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

@media (min-width: 765px) {
    .px {
        padding: 0;
    }

}
</style>