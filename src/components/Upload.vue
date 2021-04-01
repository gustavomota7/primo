<template>
    <div class="box container-fluid">
        <h1>Upload</h1>
        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniampariatur.</p>
        <div class="row">
            <div class="col"></div>
            <div class="col pilares">7 pilares do festival</div>
            <div class="col"></div>
        </div>
        <div class="row">
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
            <div class="col"></div>
            <div class="col"></div>
        </div>
        <div class="bg-color"></div>
    </div>
</template>

<style scoped>
h1 {
    padding: 50px;
    color: white;
}

p {
    color: white;
    width: 75vw;
    display: inline-block;
    padding: 40px;
}

li {
    font-weight: bold;
    list-style-type: none;
}

.box {
    position: relative;
    padding: 0;
    padding-bottom: 50px;
}

.col {
    margin:20px;
    color: white;
}

.row {
    padding: 10px;
}

.pilares {
    background-image: url("../assets/pilares.png");
    background-size: 100% 100%;
    border-radius: 20px;
    font-size: 30px;
    padding: 10px;
    max-width: 350px;
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
    transform: scaleY(1.6);
    clip-path: polygon(0 25%, 100% 0, 100% 75%, 0% 100%);
}
</style>