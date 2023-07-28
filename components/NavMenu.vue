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
        <div class="other-icons nav-items-width fixed">
            <div class="btn">
                <div class="icons">
                    <a href="#">
                        <span class="label">
                            <SVGHome />
                            <p>Home</p>
                        </span>
                    </a>
                </div>
            </div>
            <div class="mobile-hide btn">
                <div class="icons">
                    <a href="#">
                        <span class="label">
                            <SVGSearch />
                            <p>Search</p>
                        </span>
                    </a>
                </div>
            </div>
            <div class="btn">
                <div class="icons">
                    <a href="#">
                        <span class="label">
                            <SVGExplore />
                            <p>Explore</p>
                        </span>
                    </a>
                </div>
            </div>
            <div class="btn">
                <div class="icons">
                    <a href="#">
                        <span class="label">
                            <SVGReels />
                            <p>Reels</p>
                        </span>
                    </a>
                </div>
            </div>
            <div class="btn">
                <div class="icons">
                    <a href="#">
                        <span class="label">
                            <SVGMessenger />
                            <p>Messeges</p>
                        </span>
                    </a>
                </div>
            </div>
            <div class="mobile-hide btn">
                <div class="icons">
                    <a href="#">
                        <span class="label">
                            <SVGNotification />
                            <p>Notifications</p>
                        </span>
                    </a>
                </div>
            </div>
            <div class="btn">
                <div class="icons">
                    <a href="#">
                        <span class="label">
                            <SVGNewPost />
                            <p>Create</p>
                        </span>
                    </a>
                </div>
            </div>
            <div class="btn">
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
        <div class="setting nav-items-width mobile-hide btn">
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
    <nav class="nav-mobile">
        <div class="logo-mobile">
            <a href="#">
                <span>
                    <SVGInstagram />
                </span>
            </a>
        </div>
        <input class="search" type="text" placeholder="Search">
        <div>
            <a href="#">
                <span>
                    <SVGNotification />
                </span>
            </a>
        </div>
    </nav>
    <nav class="bottom-nav-mobile fixed fixed-width bg-white">
        <MobileNavMenu />
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

.search {
    padding: 0.6rem;
    margin-right: 1rem;
    border: none;
    background: #e6e6e6;
    border-radius: 4px;
}

.btn {
    width: 100%;
}

.bg-white {
    background-color: #fff;
}

.fixed-width {
    width: 100%;
}

.fixed {
    position: fixed;
    bottom: 0;
    left: 50%;
    transform: translate(-50%, 0);
}

.nav {
    display: none;
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

.bottom-nav-mobile {
    /* display: flex; */
    padding-bottom: 1rem;
    padding-top: 1rem;
    padding-left: 1.3rem;
    padding-right: 1.3rem;
    align-items: center;
    border-top: 2px solid #e6e6e6;
}

.mobile-hide {
    display: none;
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

.logo-mobile {
    flex-grow: 1;
}

/* .fixed {
    position: fixed;
    bottom: 0%;
    left: 50%;
    transform: translate(-50%, -50%);
    background-color: white;
} */


@media (min-width: 765px) {
    .fixed {
        position: inherit;
        bottom: inherit;
        left: inherit;
        transform: inherit;
    }

    .nav-mobile,
    .bottom-nav-mobile {
        display: none;
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
        display: block;
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

    .mobile-hide {
        display: block;
    }

    .other-icons {
        flex-grow: 1;
        flex-direction: column;
        justify-content: flex-start;
    }
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

    .other-icons {
        align-items: flex-start;
    }
}
</style>
