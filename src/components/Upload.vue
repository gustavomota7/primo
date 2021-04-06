<template>
    <div class="box container-fluid">
        <div>
            <img class="upload" src="../assets/upload.png">
        </div>
        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniampariatur.</p>
        <div class="row">
            <div class="col pilares">7 pilares do festival</div>
        </div>
        <div class="bulletp">
            <div class="col">
                <ul>
                    <li>1. Lorem ipsum dolor</li>
                    <li>2. Lorem ipsum dolor</li>
                    <li>3. Lorem ipsum dolor</li>
                    <li>4. Lorem ipsum dolor</li>
                    <li>5. Lorem ipsum dolor</li>
                    <li>5. Lorem ipsum dolor</li>
                </ul>
            </div>
            <div class="col">
                <ul>
                    <li>6. Lorem ipsum dolor</li>
                    <li>7. Lorem ipsum dolor</li>
                    <li>8. Lorem ipsum dolor</li>
                    <li>9. Lorem ipsum dolor</li>
                </ul>
            </div>
        </div>
        <div class="bg-color"></div>
    </div>
</template>

<style scoped>

.upload {
    max-height: 150px;
    max-width: 90vw;
}

p {
    color: white;
    width: 50vw;
    display: inline-block;
    padding: 40px;
    letter-spacing: 1px;
}

li {
    font-weight: bold;
    list-style-type: none;
}

.bulletp {
    display: flex;
    flex-direction: row;
    justify-content: flex-start;
    max-width: 1200px;
}


.box {
    position: relative;
    padding: 0;
    padding-bottom: 150px;
}

.col {
    margin:20px;
    color: white;
}

.row {
    padding: 10px;
    justify-content: center;
}

.pilares {
    background-image: url("../assets/pilares.png");
    font-weight: bold;
    background-size: 100% 100%;
    border-radius: 20px;
    font-size: 30px;
    padding: 10px;
    margin-bottom: 30px;
    width: 70vw;
    max-width: 300px;
    min-width: 190px;
}

.bg-color {
    position: absolute;
    background: url("../assets/gradient.png"), #ff5f00;
    background-size: 100% 100%;
    width: 100%;
    height: 100%;
    top: 0;
    z-index: -2;
    transform: scaleY(1.3) skewY(-8deg);
}

@media (max-width: 800px) {
    .bulletp {
        flex-direction: column;
        padding-bottom: 70px;
    }

    .col {
        margin: 0px;
    }

    ul {
        margin: 0px;
        padding: 0px;
    }

    .bg-color {
        height: 115%
    }

}

@media (max-width: 550px) {
    .bulletp {
        flex-direction: column;
    }

    p {
        width: 90vw;
    }

    .col {
        margin: 0px;
    }

    ul {
        margin: 0px;
        padding: 0px;
    }

    .bg-color {
        height: 115%
    }

}
</style>