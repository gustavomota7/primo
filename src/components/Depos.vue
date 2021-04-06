<template>
    <div class="box container-fluid">
        <div class="depoimentos">

            <div class="depo depo-first">
                <div class="texto">
                    <h1>Lorem Ipsum</h1>
                    <h5>Lorem Ipsum Dolor</h5>
                    <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eialiqua. Ut enim ad minim veniam, quis exercitation 
                    ullamco laboris nisi ut aliquip ex ea commodo consequat.</p>
                </div>
                <div class="foto"><img class="imagem" src="../assets/dep1.png"></div>
            </div>

            <div class="depo reverse">
                <div class="texto">
                    <h1 class="orange">Lorem Ipsum</h1>
                    <h5>Lorem Ipsum Dolor</h5>
                    <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eialiqua. Ut enim ad minim veniam, quis exercitation 
                    ullamco laboris nisi ut aliquip ex ea commodo consequat.</p>
                </div>
                <div class="foto"><img class="imagem" src="../assets/dep2.png"></div>
            </div>

            <div class="depo">
                <div class="texto">
                    <h1 class="orange">Lorem Ipsum</h1>
                    <h5>Lorem Ipsum Dolor</h5>
                    <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eialiqua. Ut enim ad minim veniam, quis exercitation 
                    ullamco laboris nisi ut aliquip ex ea commodo consequat.</p>
                </div>
                <div class="foto"><img class="imagem" src="../assets/dep3.png"></div>
            </div>

            <div class="depo reverse">
                <div class="texto">
                    <h1 class="orange">Lorem Ipsum</h1>
                    <h5>Lorem Ipsum Dolor</h5>
                    <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eialiqua. Ut enim ad minim veniam, quis exercitation 
                    ullamco laboris nisi ut aliquip ex ea commodo consequat.</p>
                </div>
                <div class="foto"><img class="imagem" src="../assets/dep4.png"></div>
            </div>

            <div class="depo">
                <div class="texto">
                    <h1 class="orange">Lorem Ipsum</h1>
                    <h5>Lorem Ipsum Dolor</h5>
                    <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eialiqua. Ut enim ad minim veniam, quis exercitation 
                    ullamco laboris nisi ut aliquip ex ea commodo consequat.</p>
                </div>
                <div class="foto"><img class="imagem" src="../assets/dep5.png"></div>
            </div>

            <div class="depo reverse">
                <div class="texto">
                    <h1 class="orange">Lorem Ipsum</h1>
                    <h5>Lorem Ipsum Dolor</h5>
                    <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eialiqua. Ut enim ad minim veniam, quis exercitation 
                    ullamco laboris nisi ut aliquip ex ea commodo consequat.</p>
                </div>
                <div class="foto"><img class="imagem" src="../assets/dep6.png"></div>
            </div>

            <div class="depo">
                <div class="texto">
                    <h1 class="orange">Lorem Ipsum</h1>
                    <h5>Lorem Ipsum Dolor</h5>
                    <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eialiqua. Ut enim ad minim veniam, quis exercitation 
                    ullamco laboris nisi ut aliquip ex ea commodo consequat.</p>
                </div>
                <div class="foto"><img class="imagem" src="../assets/dep7.png"></div>
            </div>

            <div class="depo reverse">
                <div class="texto">
                    <h1 class="orange">Lorem Ipsum</h1>
                    <h5>Lorem Ipsum Dolor</h5>
                    <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eialiqua. Ut enim ad minim veniam, quis exercitation 
                    ullamco laboris nisi ut aliquip ex ea commodo consequat.</p>
                </div>
                <div class="foto"><img class="imagem" src="../assets/dep8.png"></div>
            </div>

            <div class="depo depo-last">
                <div class="texto-last">
                    <h1 class="orange">Lorem Ipsum</h1>
                    <h5>Lorem Ipsum Dolor</h5>
                    <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eialiqua. Ut enim ad minim veniam, quis exercitation 
                    ullamco laboris nisi ut aliquip ex ea commodo consequat.</p>
                </div>
                <div class="foto-last">
                    <picture class="imagem">
                        <source media="(min-width: 800px)" srcset="../assets/depbig.png">
                        <img class="imagem" src="../assets/depsmall.png" alt="mobile">
                    </picture>
                </div>

            </div>

        </div>
    </div>
</template>

<style scoped>


h1 {
    padding-top: 30px;
    margin: 0;
    font-weight: bold;
}

.orange {
    padding-top: 0px; 
    color: #ff5f00;
}

h5 {
    margin-bottom: 50px;
}

p {
    padding-left: 50px;
    padding-right: 70px;
    line-height: 150%;
    letter-spacing: 1px;
}


.box {
    position: relative;
    margin-top: -210px;
}

.depoimentos {
    display: flex;
    flex-direction: column;
}

.depo {
    display: flex;
    flex-direction: row;
    justify-content: center;
    align-items: flex-start;
    padding: 50px;
}

.depo-first {
    color: white;
}

.depo-last {
    flex-direction: column;
    padding-bottom: 0%;
}

.reverse {
    flex-direction: row-reverse;
}

.texto {
    flex-grow: 3;
    padding: 0px;
}

.texto-last {
    align-self: center;
    padding: 0px;
}

.foto {
    flex-grow: 2;
    align-self: center;
}

.foto-last {
    align-self: center;
}

.imagem {
    max-height: 300px;
    max-width: 75vw;
    padding-top: 10px;

}


@media (max-width: 550px) {
    p {
        padding: 0;
    }

}

@media (max-width: 800px) {
    .depo {
        flex-direction: column;
    }

}

@media (min-width: 1200px) {
    .depo {
        justify-self: center;
        align-self: center;
        max-width: 1200px;
    }

}


</style>