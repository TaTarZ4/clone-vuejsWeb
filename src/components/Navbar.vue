<template lang="">
    <div class="navbar">
        <div class="menu-logo">
            <img alt="Vue logo" class="logo" src="@/assets/logo.svg" width="24" height="24" />
            <div class="text">Vue.js</div>
        </div>
        <div class="menu">
            <button type="button" class="search" @click="alert = !alert">
                <div class="search-icon">
                    <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="bi bi-search" viewBox="0 0 16 16">
                        <path d="M11.742 10.344a6.5 6.5 0 1 0-1.397 1.398h-.001q.044.06.098.115l3.85 3.85a1 1 0 0 0 1.415-1.414l-3.85-3.85a1 1 0 0 0-.115-.1zM12 6.5a5.5 5.5 0 1 1-11 0 5.5 5.5 0 0 1 11 0"/>
                    </svg>
                </div>
                <div class="text">Search</div>
                <div class="shortcut"><div>Ctrl</div><div>K</div></div>
            </button>
            <div class="menu-list">
                <div class="dropdow">
                    <div class="dropdow-text">
                        <span>Docs</span>
                        <div class="arrow">
                            <svg xmlns="http://www.w3.org/2000/svg" width="14" height="14" fill="currentColor" class="bi bi-chevron-down" viewBox="0 0 16 16">
                                <path fill-rule="evenodd" d="M1.646 4.646a.5.5 0 0 1 .708 0L8 10.293l5.646-5.647a.5.5 0 0 1 .708.708l-6 6a.5.5 0 0 1-.708 0l-6-6a.5.5 0 0 1 0-.708"/>
                            </svg>
                        </div>
                    </div>
                    <div class="dropdow-content">
                        <div class="dc-menu">
                            <div class="">Content 1</div>
                            <div class="">Content 2</div>
                            <div class="">Content 3</div>
                            <div class="">Content 4</div>
                            <div class="">Content 5</div>
                            <div class="">Content 6</div>
                        </div>
                    </div>
                </div>
                <div class="text">API</div>
                <div class="text">Playground</div>
                <div class="dropdow">
                    <div class="dropdow-text">
                        <span>Ecosystem</span>
                        <div class="arrow">
                            <svg xmlns="http://www.w3.org/2000/svg" width="14" height="14" fill="currentColor" class="bi bi-chevron-down" viewBox="0 0 16 16">
                                <path fill-rule="evenodd" d="M1.646 4.646a.5.5 0 0 1 .708 0L8 10.293l5.646-5.647a.5.5 0 0 1 .708.708l-6 6a.5.5 0 0 1-.708 0l-6-6a.5.5 0 0 1 0-.708"/>
                            </svg>
                        </div>
                    </div>
                    <div class="dropdow-content">
                        <div class="dc-menu">
                            <div class="">Content 1</div>
                            <div class="">Content 2</div>
                            <div class="">Content 3</div>
                            <div class="">Content 4</div>
                            <div class="">Content 5</div>
                            <div class="">Content 6</div>
                        </div>
                    </div>
                </div>
                <div class="dropdow">
                    <div class="dropdow-text">
                        <span>about</span>
                        <div class="arrow">
                            <svg xmlns="http://www.w3.org/2000/svg" width="14" height="14" fill="currentColor" class="bi bi-chevron-down" viewBox="0 0 16 16">
                                <path fill-rule="evenodd" d="M1.646 4.646a.5.5 0 0 1 .708 0L8 10.293l5.646-5.647a.5.5 0 0 1 .708.708l-6 6a.5.5 0 0 1-.708 0l-6-6a.5.5 0 0 1 0-.708"/>
                            </svg>
                        </div>
                    </div>
                    <div class="dropdow-content">
                        <div class="dc-menu">
                            <div class="">Content 1</div>
                            <div class="">Content 2</div>
                            <div class="">Content 3</div>
                            <div class="">Content 4</div>
                            <div class="">Content 5</div>
                            <div class="">Content 6</div>
                        </div>
                    </div>
                </div>
                <div class="text">sponsor</div>
                <div class="text">partners</div>
                <div class="translate">
                    <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" fill="currentColor" class="bi bi-translate" viewBox="0 0 16 16">
                        <path d="M4.545 6.714 4.11 8H3l1.862-5h1.284L8 8H6.833l-.435-1.286zm1.634-.736L5.5 3.956h-.049l-.679 2.022z"/>
                        <path d="M0 2a2 2 0 0 1 2-2h7a2 2 0 0 1 2 2v3h3a2 2 0 0 1 2 2v7a2 2 0 0 1-2 2H7a2 2 0 0 1-2-2v-3H2a2 2 0 0 1-2-2zm2-1a1 1 0 0 0-1 1v7a1 1 0 0 0 1 1h7a1 1 0 0 0 1-1V2a1 1 0 0 0-1-1zm7.138 9.995q.289.451.63.846c-.748.575-1.673 1.001-2.768 1.292.178.217.451.635.555.867 1.125-.359 2.08-.844 2.886-1.494.777.665 1.739 1.165 2.93 1.472.133-.254.414-.673.629-.89-1.125-.253-2.057-.694-2.82-1.284.681-.747 1.222-1.651 1.621-2.757H14V8h-3v1.047h.765c-.318.844-.74 1.546-1.272 2.13a6 6 0 0 1-.415-.492 2 2 0 0 1-.94.31"/>
                    </svg>
                </div>
                <button class="appearance">
                    <div class="icon-moon">
                        <svg xmlns="http://www.w3.org/2000/svg" width="12" height="12" fill="currentColor" class="bi bi-moon" viewBox="0 0 16 16">
                            <path d="M6 .278a.77.77 0 0 1 .08.858 7.2 7.2 0 0 0-.878 3.46c0 4.021 3.278 7.277 7.318 7.277q.792-.001 1.533-.16a.79.79 0 0 1 .81.316.73.73 0 0 1-.031.893A8.35 8.35 0 0 1 8.344 16C3.734 16 0 12.286 0 7.71 0 4.266 2.114 1.312 5.124.06A.75.75 0 0 1 6 .278M4.858 1.311A7.27 7.27 0 0 0 1.025 7.71c0 4.02 3.279 7.276 7.319 7.276a7.32 7.32 0 0 0 5.205-2.162q-.506.063-1.029.063c-4.61 0-8.343-3.714-8.343-8.29 0-1.167.242-2.278.681-3.286"/>
                        </svg>
                    </div>
                </button>
                <div class="github">
                    <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" fill="currentColor" class="bi bi-github" viewBox="0 0 16 16">
                        <path d="M8 0C3.58 0 0 3.58 0 8c0 3.54 2.29 6.53 5.47 7.59.4.07.55-.17.55-.38 0-.19-.01-.82-.01-1.49-2.01.37-2.53-.49-2.69-.94-.09-.23-.48-.94-.82-1.13-.28-.15-.68-.52-.01-.53.63-.01 1.08.58 1.23.82.72 1.21 1.87.87 2.33.66.07-.52.28-.87.51-1.07-1.78-.2-3.64-.89-3.64-3.95 0-.87.31-1.59.82-2.15-.08-.2-.36-1.02.08-2.12 0 0 .67-.21 2.2.82.64-.18 1.32-.27 2-.27s1.36.09 2 .27c1.53-1.04 2.2-.82 2.2-.82.44 1.1.16 1.92.08 2.12.51.56.82 1.27.82 2.15 0 3.07-1.87 3.75-3.65 3.95.29.25.54.73.54 1.48 0 1.07-.01 1.93-.01 2.2 0 .21.15.46.55.38A8.01 8.01 0 0 0 16 8c0-4.42-3.58-8-8-8"/>
                    </svg>
                </div>
                <div class="x">
                    <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" fill="currentColor" class="bi bi-twitter-x" viewBox="0 0 16 16">
                        <path d="M12.6.75h2.454l-5.36 6.142L16 15.25h-4.937l-3.867-5.07-4.425 5.07H.316l5.733-6.57L0 .75h5.063l3.495 4.633L12.601.75Zm-.86 13.028h1.36L4.323 2.145H2.865z"/>
                    </svg>
                </div>
                <div class="discord">
                    <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" fill="currentColor" class="bi bi-discord" viewBox="0 0 16 16">
                        <path d="M13.545 2.907a13.2 13.2 0 0 0-3.257-1.011.05.05 0 0 0-.052.025c-.141.25-.297.577-.406.833a12.2 12.2 0 0 0-3.658 0 8 8 0 0 0-.412-.833.05.05 0 0 0-.052-.025c-1.125.194-2.22.534-3.257 1.011a.04.04 0 0 0-.021.018C.356 6.024-.213 9.047.066 12.032q.003.022.021.037a13.3 13.3 0 0 0 3.995 2.02.05.05 0 0 0 .056-.019q.463-.63.818-1.329a.05.05 0 0 0-.01-.059l-.018-.011a9 9 0 0 1-1.248-.595.05.05 0 0 1-.02-.066l.015-.019q.127-.095.248-.195a.05.05 0 0 1 .051-.007c2.619 1.196 5.454 1.196 8.041 0a.05.05 0 0 1 .053.007q.121.1.248.195a.05.05 0 0 1-.004.085 8 8 0 0 1-1.249.594.05.05 0 0 0-.03.03.05.05 0 0 0 .003.041c.24.465.515.909.817 1.329a.05.05 0 0 0 .056.019 13.2 13.2 0 0 0 4.001-2.02.05.05 0 0 0 .021-.037c.334-3.451-.559-6.449-2.366-9.106a.03.03 0 0 0-.02-.019m-8.198 7.307c-.789 0-1.438-.724-1.438-1.612s.637-1.613 1.438-1.613c.807 0 1.45.73 1.438 1.613 0 .888-.637 1.612-1.438 1.612m5.316 0c-.788 0-1.438-.724-1.438-1.612s.637-1.613 1.438-1.613c.807 0 1.451.73 1.438 1.613 0 .888-.631 1.612-1.438 1.612"/>
                    </svg>
                </div>
            </div>
        </div>
    </div>
    <!-- <div class="navbar-line"/> -->
    <div class="alert" v-if="alert">
        <div class="alert-input">
            <div class="search-icon">
                <svg xmlns="http://www.w3.org/2000/svg" width="25" height="25" fill="currentColor" class="bi bi-search" viewBox="0 0 16 16">
                    <path d="M11.742 10.344a6.5 6.5 0 1 0-1.397 1.398h-.001q.044.06.098.115l3.85 3.85a1 1 0 0 0 1.415-1.414l-3.85-3.85a1 1 0 0 0-.115-.1zM12 6.5a5.5 5.5 0 1 1-11 0 5.5 5.5 0 0 1 11 0"/>
                </svg>
            </div>
            <input type="text" class="input" v-model="inputSearch" placeholder="Search docs"/>
        </div>
        <div class="recent">
            <div class="recent-text">recent</div>
            <div class="recent-list">
                <div class="list-card" v-for="(item , key) in 10" :key="key">
                    <div class="icon-clock">
                        <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="bi bi-clock-history" viewBox="0 0 16 16">
                            <path d="M8.515 1.019A7 7 0 0 0 8 1V0a8 8 0 0 1 .589.022zm2.004.45a7 7 0 0 0-.985-.299l.219-.976q.576.129 1.126.342zm1.37.71a7 7 0 0 0-.439-.27l.493-.87a8 8 0 0 1 .979.654l-.615.789a7 7 0 0 0-.418-.302zm1.834 1.79a7 7 0 0 0-.653-.796l.724-.69q.406.429.747.91zm.744 1.352a7 7 0 0 0-.214-.468l.893-.45a8 8 0 0 1 .45 1.088l-.95.313a7 7 0 0 0-.179-.483m.53 2.507a7 7 0 0 0-.1-1.025l.985-.17q.1.58.116 1.17zm-.131 1.538q.05-.254.081-.51l.993.123a8 8 0 0 1-.23 1.155l-.964-.267q.069-.247.12-.501m-.952 2.379q.276-.436.486-.908l.914.405q-.24.54-.555 1.038zm-.964 1.205q.183-.183.35-.378l.758.653a8 8 0 0 1-.401.432z"/>
                            <path d="M8 1a7 7 0 1 0 4.95 11.95l.707.707A8.001 8.001 0 1 1 8 0z"/>
                            <path d="M7.5 3a.5.5 0 0 1 .5.5v5.21l3.248 1.856a.5.5 0 0 1-.496.868l-3.5-2A.5.5 0 0 1 7 9V3.5a.5.5 0 0 1 .5-.5"/>
                        </svg>
                    </div>
                    <div class="text">recent {{item}}</div>
                </div>
            </div>
        </div>
    </div>
    <div class="overlay" v-if="alert" @click="alert=!alert"></div>
</template>
<script setup >
    import { ref } from 'vue';
    const alert = ref(false)
    const inputSearch = ref("")
</script>
<style scoped>
    .navbar {
        position: sticky;
        top: 0;
        background: #1a1a1a;
        display: flex;
        padding: 1rem;
        padding-left: 4rem;
        padding-right: 4rem;
        border-bottom: 1px solid #525252;
        width: 100vw;
    }
    .menu-logo {
        display: flex;

        .text {
            font-weight: 400;
            margin-left: 8px;
            margin-right: 1.5rem;
            margin-top: 2px;
            font-size: 1rem;
        }
    }

    .menu-logo:hover {
        filter: grayscale(50%);
        color: #525252;
    }
    .navbar-line {
        position: absolute;
        width: 100vw;
        left: 0;
        border-top: 1px solid #525252;
    }
    .menu {
        display: flex;
        justify-content: space-between;
        width: 100%;
    }
    .menu-list {
        display: flex;
        gap: 1.5rem;
        font-size: small;
        align-items: center;

        .text:hover {
            color: #1aec87;
        }
        .translate {
            border-right: 1px solid #525252;
            border-left: 1px solid #525252;
            height: 100%;
            padding-left: 0.75rem;
            padding-right: 0.75rem;
        }

        .dropdow {
            position: relative;

            .dropdow-text {
                display: flex;
                gap: 0.25rem;

                .arrow {
                    width: 14px;
                    height: 14px;
                }
            }

            .dropdow-content{
                display: none;
                position: absolute;
                right: 0;
                width: 10rem;
                background: #1a1a1a;
                z-index: 1;

                .dc-menu {
                    margin-top: 0.5rem;
                    border: 1px solid #525252;
                    border-radius: 0.5rem;
                    display: flex;
                    flex-direction: column;
                    padding: 0.25rem;
                    div {
                        margin: 0.5rem;
                    }
                    div:hover {
                        color: #1aec87;
                    }
                }
            }
        }

        .dropdow:hover .dropdow-text {
            color: #525252;
        }
        .dropdow:hover .dropdow-content{
            display: block;
        }
    }
    .search {
        display: flex;
        align-items: center;
        font-size: small;
        gap: 0.75rem;
        color: #525252;
        background: #1a1a1a;
        border: #1a1a1a;
        
        .shortcut {
            display: flex;
            justify-content: space-between;
            border: 1px solid #525252;
            border-radius: 5px;
            padding-left: 5px;
            gap: 2px;
            padding-right: 5px;
            padding: 2px;
        }
        .search-icon {
            padding-top: 2px;
        }
    }
    .search:hover {
        color: white;
        .shortcut {
            color: #1aec87;
            border:1px solid #1aec87;
        }
    }
    .translate , .x , .github , .appearance , .discord {
        color: #a0a0a0;
    }
    .translate:hover , .x:hover , .github:hover , .discord:hover {
        color: white;
    }
    .appearance {
        width: 40px;
        height: 22px;
        border-radius: 11px;
        background: #84848465;
        border: 1px solid #a0a0a0;
        position: relative;
        .icon-moon{
            border-radius: 50px;
            position: absolute;
            right: 0;
            top: 0;
            background: black;
            color: white;
            width: 18px;
            height: 18px;
            margin: 1px;
            display: flex;
            justify-content: center;
            align-items: center;
        }
    }
    .appearance:hover {
        color: white;
        border: 1px solid white;
    }

    .alert {
        position: absolute;
        top: 50%;
        left: 50%;
        transform: translate(-50% , -50%);
        z-index: 1;
        background: #1a1a1a;
        padding: 1rem;
        border-radius: 8px;
        width: 560px;

        .alert-input {
            display: flex;
            align-items: center;
            padding: 1rem;
            border: 1px solid #1aec87;
            background: #2a2a2a;
            gap: 0.5rem;
            border-radius: 4px;
        }
        
        .input {
            font-size: 23px;
            background: #2a2a2a;
            width: 100%;
            border: none;
            outline: none;
            color: white;
        }

        .recent-text {
            margin-top: 1rem;
            margin-bottom: 0.5rem;
            color: #1aec87;
        }

        .recent-list {
            display: flex;
            flex-direction: column;
            gap: 5px;
        }

        .list-card {
            display: flex;
            align-items: center;
            gap: 1rem;
            padding: 0.75rem;
            background: #2a2a2a;
            border-radius: 4px;
            
            .icon-clock {
                display: flex;
                align-items: center;
            }
        }

        .list-card:hover {
            background: #1aec87;
        }
    }
    .overlay {
        position: fixed;
        width: 100%;
        height: 100%;
        top: 0;
        right: 0;
        background: #d0d5ff3c;
    }
</style>