<template>
    <div>
        <div class="box container-fluid">
            <div class="logo container-fluid">
                <img class="arrow" src="../assets/arrow.png">
            </div>

            <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor 
                incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud 
                exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.</p>

            <div class="ball">
                <img class="bola" src="../assets/bola.png">
            </div>

        </div>
    </div>
</template>

<style scoped>

p {
    max-width: 50vw;
    text-align: center;
    display: inline-block;
    padding: 40px;
}

.box {
    margin-top: 2vw;
    position: relative;
    z-index: -1;
    padding: 0;
}

.arrow {
    max-width: 50px;
    width: 7vw;
}

.ball {
    position: relative;
}

.bola {
    max-width: 500px;
}

@media (max-width: 550px) {
    p {
        max-width: 90vw;
    }

    .bola {
        max-width: 320px;
    }

    .ball {
        padding-bottom: 50px;
    }
}


</style>