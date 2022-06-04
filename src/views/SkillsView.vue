<template>
    <div class="skills">
        <div class="content-cus">
        <div class="animate__animated animate__bounceInDown">
            <p class="mb-0">HTML, CSS, BOOTSTRAP, TAILWIND</p>
            <div class="progress w-100 w-md-75 mb-3 mb-md-4">
                <div class="progress-bar progress-bar-striped progress-bar-animated" role="progressbar" aria-valuenow="85" aria-valuemin="0" aria-valuemax="100" style="width: 85%"></div>
            </div>
        </div>
        <div class="animate__animated animate__bounceInDown delay-1">
            <p class="mb-0">JavaScript, JQuery, VueJs</p>
            <div class="progress w-100 w-md-75 mb-3 mb-md-4">
                <div class="progress-bar progress-bar-striped progress-bar-animated" role="progressbar" aria-valuenow="75" aria-valuemin="0" aria-valuemax="100" style="width: 75%"></div>
            </div>
        </div>
        <div class="animate__animated animate__bounceInDown delay-2">
            <p class="mb-0">Mysql, PHP, Laravel</p>
            <div class="progress w-100 w-md-75 mb-3 mb-md-4">
                <div class="progress-bar progress-bar-striped progress-bar-animated" role="progressbar" aria-valuenow="80" aria-valuemin="0" aria-valuemax="100" style="width: 80%"></div>
            </div>
        </div>
        <div class="animate__animated animate__bounceInDown delay-3">
            <p class="mb-0">Microsoft Word, Excel, Powerpoint</p>
            <div class="progress w-100 w-md-75 mb-3 mb-md-4">
                <div class="progress-bar progress-bar-striped progress-bar-animated" role="progressbar" aria-valuenow="75" aria-valuemin="0" aria-valuemax="100" style="width: 75%"></div>
            </div>
        </div>
        <div class="animate__animated animate__bounceInDown delay-4">
            <p class="mb-0">Adobe Xd, Figma, Ai, Ps</p>
            <div class="progress w-100 w-md-75 mb-3 mb-md-4">
                <div class="progress-bar progress-bar-striped progress-bar-animated" role="progressbar" aria-valuenow="50" aria-valuemin="0" aria-valuemax="100" style="width: 50%"></div>
            </div>
        </div>
        </div>
    </div>
</template>

<style lang="scss" scoped>
    .skills {
        width: 100%;
        height: 100%;
        padding: 0 100px;
        display: grid;
        place-items: center;
    }
    .content-cus {
        width: 100%;
    }
    .delay-1 {
        animation-delay: 0.2s;
    }
    .delay-2 {
        animation-delay: 0.4s;
    }
    .delay-3 {
        animation-delay: 0.6s;
    }
    .delay-4 {
        animation-delay: 0.8s;
    }
    @media screen and (max-width: 500px) {
        .skills {
            padding: 0 50px;
        }
    }
</style>