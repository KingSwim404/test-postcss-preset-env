<template>
    <div id="app">

        <div id="test">

        </div>

    </div>
</template>

<style>

    html, body {
        padding: 0;
        margin: 0;
        width: 100%;
        height: 100%;
    }

    #app {
        font-family: 'Avenir', Helvetica, Arial, sans-serif;
        -webkit-font-smoothing: antialiased;
        -moz-osx-font-smoothing: grayscale;
        text-align: center;
        background-color: var(--main-color);
        width: 100%;
        height: 100%;
    }

    #test {
        width: 100px;
        height: 100px;
        background-color: yellow;
    }

    @media (--mobile-media) {
        #test {
            height: 200px;
            background-color: var(--mobile-color);
        }

    }

</style>
