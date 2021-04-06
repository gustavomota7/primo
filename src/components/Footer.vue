<template>
    <div class="box container-fluid">
        <div class="logo container-fluid">
            <img class="logo" src="../assets/logo.png">
        </div>
        <div class="bg-color"></div>
    </div>
</template>

<style scoped>
.logo {
    padding: 25px;
    padding-top: 250px;
    width: 100%;
    max-width: 450px;
}


.box {
    margin-top: -250px;
    position: relative;
    padding: 0;
    padding-bottom: 5vw;
    z-index: -1;
}

.bg-color {
    position: absolute;
    background: url("../assets/footerbg.png"), #ff5f00;
    background-size: 100% 100%;
    width: 100%;
    height: 100%;
    top: 0;
    z-index: -1;
    clip-path: polygon(0% 35%, 100% 0%, 100% 100%, 0% 100%);
}

@media (max-width: 800px) {
    .box {
        margin-top: -250px;
    }

}

</style>