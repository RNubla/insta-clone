<template>
    <nav class="nav">
        <div class="logo nav-items-width">
            <div class="icons">
                <a href="#">
                    <div class="logo-label">
                        <SVGLogo />
                    </div>
                    <div class="logo-instagram">
                        <SVGInstagram />
                    </div>
                </a>
            </div>
        </div>
        <div class="other-icons nav-items-width">
            <div>
                <div class="icons">
                    <a href="#">
                        <span class="label">
                            <SVGHome />
                            <p>Home</p>
                        </span>
                    </a>
                </div>
            </div>
            <div>
                <div class="icons">
                    <a href="#">
                        <span class="label">
                            <SVGSearch />
                            <p>Search</p>
                        </span>
                    </a>
                </div>
            </div>
            <div>
                <div class="icons">
                    <a href="#">
                        <span class="label">
                            <SVGExplore />
                            <p>Explore</p>
                        </span>
                    </a>
                </div>
            </div>
            <div>
                <div class="icons">
                    <a href="#">
                        <span class="label">
                            <SVGReels />
                            <p>Reels</p>
                        </span>
                    </a>
                </div>
            </div>
            <div>
                <div class="icons">
                    <a href="#">
                        <span class="label">
                            <SVGMessenger />
                            <p>Messeges</p>
                        </span>
                    </a>
                </div>
            </div>
            <div>
                <div class="icons">
                    <a href="#">
                        <span class="label">
                            <SVGNotification />
                            <p>Notifications</p>
                        </span>
                    </a>
                </div>
            </div>
            <div>
                <div class="icons">
                    <a href="#">
                        <span class="label">
                            <SVGNewPost />
                            <p>Create</p>
                        </span>
                    </a>
                </div>
            </div>
            <div>
                <div class="icons">
                    <a href="#">
                        <span class="label">
                            <SVGNewPost />
                            <p>Profile</p>
                        </span>
                    </a>
                </div>
            </div>
        </div>
        <div class="setting nav-items-width">
            <div>
                <div class="icons">
                    <a href="#">
                        <span class="label">
                            <SVGHamburger />
                            <p>More</p>
                        </span>
                    </a>
                </div>
            </div>
        </div>
    </nav>
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

.label {
    display: flex;
    justify-content: flex-start;
    align-items: flex-end;
    font-weight: 400;
}

.label p {
    display: none;

}

.icons {
    display: flex;
    justify-content: center;
    align-items: center;
    transition: all 0.5s;
}

.icons:hover {
    background-color: #e6e6e6;
    border-radius: 6px;
}

.icons a {
    padding: 0.8rem;

}

.icons:hover svg {
    transform: scale(1.2);
}

.nav-items-width {
    width: 100%;
}

.setting {
    justify-content: flex-end;
}

.logo-instagram {
    display: none;
}

.logo-label {
    display: flex;
    justify-content: center;
    align-items: center;
    gap: 1.5rem;
}

.logo {
    height: 92px;
    flex-shrink: 0;
}

.nav {
    display: flex;
    flex-direction: column;
    align-items: flex-start;
    padding: 2rem 0.7rem;
    border-right: 2px solid #e6e6e6;
}

.other-icons {
    flex-grow: 1;
}




@media (min-width: 1250px) {
    .label p {
        display: block;
        padding: 0 0 0 1rem;
    }

    .logo-label {
        display: none;
    }

    .logo-instagram {
        display: block;
    }

    .icons {
        justify-content: flex-start;
    }
}
</style>
