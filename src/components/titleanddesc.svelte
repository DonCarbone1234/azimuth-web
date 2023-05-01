<script>
    export let titletext; 
    export let desctext;
</script>

<body>
    <div class="middlebox1">
        <div class="topmiddlebox1">
            <h1> <span class="majorwhite">{titletext}</span></h1>
        </div>
        <p><span class="minorwhite">{desctext}</span></p>
    </div>
</body>

<style>
     .topmiddlebox1 {
        text-align: center;
    }

    .middlebox1 {
        padding-top: 50px;
        padding-bottom: 100px;
    }

    .majormajorwhite{
        color: #111;
        font-size: 90px;
        font-weight: 7000;
        text-align: center;
    }

    .minorwhite {
        color: #111;
        font-size: 25px;
        text-align: left;
    }

    .majorwhite {
        color: #111;
        font-size: 45px;
        font-weight: 700;
        text-align: center;
    }


</style>






