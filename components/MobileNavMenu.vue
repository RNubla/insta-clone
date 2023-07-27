<template>
    <div class="other-icons nav-items-width ">
        <div>
            <div class="icons-mobile">
                <a href="#">
                    <span class="label">
                        <SVGHome />
                        <p>Home</p>
                    </span>
                </a>
            </div>
        </div>
        <div>
            <div class="icons-mobile">
                <a href="#">
                    <span class="label">
                        <SVGExplore />
                        <p>Explore</p>
                    </span>
                </a>
            </div>
        </div>
        <div>
            <div class="icons-mobile">
                <a href="#">
                    <span class="label">
                        <SVGReels />
                        <p>Reels</p>
                    </span>
                </a>
            </div>
        </div>
        <div>
            <div class="icons-mobile">
                <a href="#">
                    <span class="label">
                        <SVGNewPost />
                        <p>Create</p>
                    </span>
                </a>
            </div>
        </div>
        <div>
            <div class="icons-mobile">
                <a href="#">
                    <span class="label">
                        <SVGMessenger />
                        <p>Messeges</p>
                    </span>
                </a>
            </div>
        </div>
        <div>
            <div class="icons-mobile">
                <a href="#">
                    <span class="label">
                        <SVGNewPost />
                        <p>Profile</p>
                    </span>
                </a>
            </div>
        </div>
    </div>
</template>

<style scoped>
/* Link tags */
a:link,
a:visited,
a:hover,
a:active {
    text-decoration: none;
    color: black;
}



.nav-mobile {
    display: flex;
    padding-bottom: 1rem;
    padding-top: 1rem;
    padding-left: 1.3rem;
    padding-right: 1.3rem;
    border-bottom: 2px solid #e6e6e6;
    align-items: center;
}


.other-icons {
    display: flex;
    justify-content: space-evenly;
    align-items: center;

}

.other-icons p {
    display: none;
}

.logo {
    display: none;
}
</style>