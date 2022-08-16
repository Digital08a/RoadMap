<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="/blob/main/templates/style.css">
</head>

<body>
    <header>
        <h1> RoadMap</h1>
    </header>
    <main>
        <h2></h2>
        <div class="galeria">
            <input type="radio" name="navegacion" id="1" checked>
            <input type="radio" name="navegacion" id="2">
            <input type="radio" name="navegacion" id="3">
            <input type="radio" name="navegacion" id="4">
            <input type="radio" name="navegacion" id="5">
            <img src="https://github.com/Digital08a/RoadMap/blob/main/templates/1.jpg" alt="portada">
            <img src="https://github.com/Digital08a/RoadMap/blob/main/templates/2.jpg" alt="galeria1">
            <img src="https://github.com/Digital08a/RoadMap/blob/main/templates/3.jpg" alt="galeria3">
            <img src="https://github.com/Digital08a/RoadMap/blob/main/templates/4.jpg" alt="galeria2">
            <img src="https://github.com/Digital08a/RoadMap/blob/main/templates/5.jpg" alt="galeria4">
        </div>
    </main>
</body>
<style>

    .galeria {
        border: 1px solid;
    border-radius: 10px;
    position: relative;
    width: 300px;
    height: 460px;
    margin: 0 auto;
}

.galeria input[type=radio] {
    position: relative;
    top: 430px;
    margin-left: 20px;
}

.galeria img {
    margin: 10px;
    border-radius: 10px;
    position: absolute;
    width: 90%;
    top: 0;
    left: 0;
    opacity: 0;
    transition: opacity 0.5s;
}
img{
    height: 420px;
}


.galeria input:nth-of-type(1):checked~img:nth-of-type(1) {
    opacity: 1;
}

.galeria input:nth-of-type(2):checked~img:nth-of-type(2) {
    opacity: 1;
}

.galeria input:nth-of-type(3):checked~img:nth-of-type(3) {
    opacity: 1;
}

.galeria input:nth-of-type(4):checked~img:nth-of-type(4) {
    opacity: 1;
}

.galeria input:nth-of-type(5):checked~img:nth-of-type(5) {
    opacity: 1;
}
</style>

</html>
