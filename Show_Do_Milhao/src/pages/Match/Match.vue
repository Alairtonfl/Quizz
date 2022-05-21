<template>
    <div>
        <button id="btnMenu">
            <img src="./icons8-back-64.png" alt="">
        </button>
        <div class="mb-3">
            <label class="form-control" id="exampleFormControlTextarea1" rows="3">
                Quanto tempo a terra demora para dar uma volta completa em torno dela mesma?
            </label>
           <div class="d-grid gap-2">
                <button type="button" class="btn btn-secondary btn-lg" > <label id="a">A</label> Aproximadamente 24 Horas</button>
                <button type="button" class="btn btn-secondary btn-lg"> <label id="b">B</label> 365 Dias </button>
                <button type="button" class="btn btn-secondary btn-lg"><label id="c">C</label> 7 Dias</button>
                <button type="button" class="btn btn-secondary btn-lg"><label id="d">D</label> 365 ou 366 Dias</button>
            </div>
        </div>
    </div>
</template>
<script src='./match.js'></script>

<style scoped>
    .form-control{
        width: 75%;
        height: 200px;
        margin-left: auto;
        margin-right: auto;
        position: relative;
        top: 90px;
        right: 70px;
        border-radius: 8px;

        background: rgb(226, 224, 224);

        font-size: 30px;
    }
    button{
        width: 75%;
        margin-left: auto;
        margin-right: auto;
        position: relative;
        top: 150px;
        right: 70px;
        border-radius: 8px;

        background: rgb(226, 224, 224);
        color: #000;
        font-size: 20px;
        text-align: start;        
    }
    #a, #b, #c, #d{
        text-align: center;
        width: 3%;
        background: yellow;
        border-radius: 50%;
    }
    #btnMenu {
        position: absolute;
        top: 2%;
        left: -20%;
        background: #000;
    }
    img{
        height: 35px;
    }
   
</style>