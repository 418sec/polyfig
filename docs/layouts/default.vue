<template>
    <div class="min-h-full min-w-full">
        <div class="container pt-24">
            <div>
                <Logo class="w-40" />
                <div class="mt-5">
                    <p class="font-semibold">
                        A simple JavaScript utility library
                    </p>
                </div>
                <div class="mt-5 block">
                    <a href="https://www.npmjs.com/package/polyfig">
                        <img
                            class="inline-block"
                            alt="version"
                            src="https://img.shields.io/npm/v/polyfig?color=%23301934"
                    /></a>
                    <a href="https://en.wikipedia.org/wiki/MIT_License">
                        <img
                            class="inline-block"
                            alt="license"
                            src="https://img.shields.io/npm/l/polyfig?color=%23301934"
                    /></a>
                    <a href="https://github.com/JamieSlome/polyfig">
                        <img
                            class="inline-block"
                            alt="repo_size"
                            src="https://img.shields.io/github/repo-size/JamieSlome/polyfig?color=%23301934"
                    /></a>
                </div>
                <div class="m-8">
                    <code
                        class="shadow-inner font-semibold text-sm bg-gray-200 border-gray-400 p-1 rounded"
                        >$ npm install polyfig</code
                    >
                </div>
            </div>
        </div>
        <Nuxt />
        <footer
            class="bg-fig text-white text-sm font-semibold mt-10 text-center p-10"
        >
            <div>
                Site made with
                <font-awesome-icon
                    class="text-red-500"
                    :icon="['fas', 'heart']"
                />
                by
                <a
                    class="hover:text-blue-500"
                    href="https://twitter.com/JamieSlome"
                    >JamieSlome</a
                >
            </div>
            <div class="mt-5">
                <a href="https://www.npmjs.com/package/polyfig" target="_blank"
                    ><font-awesome-icon
                        class="m-2 text-gray-400 hover:text-white"
                        size="2x"
                        :icon="['fab', 'npm']"
                /></a>
                <a href="https://github.com/JamieSlome" target="_blank"
                    ><font-awesome-icon
                        class="m-2 text-gray-400 hover:text-white"
                        size="2x"
                        :icon="['fab', 'github']"
                /></a>
                <a href="https://twitter.com/JamieSlome" target="_blank"
                    ><font-awesome-icon
                        class="m-2 text-gray-400 hover:text-white"
                        size="2x"
                        :icon="['fab', 'twitter']"
                /></a>
                <a
                    href="https://www.linkedin.com/in/jamie-izak-slome/"
                    target="_blank"
                    ><font-awesome-icon
                        class="m-2 text-gray-400 hover:text-white"
                        size="2x"
                        :icon="['fab', 'linkedin']"
                /></a>
                <a href="https://medium.com/@JamieSlome/about" target="_blank"
                    ><font-awesome-icon
                        class="m-2 text-gray-400 hover:text-white"
                        size="2x"
                        :icon="['fab', 'medium']"
                /></a>
            </div>
        </footer>
    </div>
</template>

<style>
.container {
    margin: 0 auto;
    min-height: 58vh;
    display: flex;
    justify-content: center;
    align-items: center;
    text-align: center;
    position: relative;
}

.links {
    justify-content: center;
    align-items: center;
    text-align: center;
}
</style>
