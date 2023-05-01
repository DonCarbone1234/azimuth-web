<script>

    export let toptitle;
    export let topdesc;
    export let middletext;

</script>

<body>

    <div class="topflexbox">

        <div class="toptextbackground">

            <div class="toptoptext">
                <span class="minor">{toptitle}</span>
                <br>
                <span class="major">{topdesc}</span>
            </div>

            <div class="topmiddletext">
                <p style="color: white; font-size: 40px; font-wieght: normal;">{middletext}</p>
            </div>

        </div>

    </div>

</body>

<style>

body {
        margin: 0;
        font-family: monospace;
    }

    .topflexbox {
        background-image: url('https://raw.githubusercontent.com/DonCarbone1234/azimuth-web/main/static/blue4small.svg');
        background-color: #4d526a;
        background-size: cover;
        background-attachment: fixed;
        display: flex;
        align-items: center;
        align-content: center;
        flex-wrap: nowrap;
        flex-direction: column;
        padding: 120px 0px;
        z-index: 5;
    }

    .toptextbackground {
        background-color: #383e59ff;
        padding: 50px 60px;
        max-width: 650px;
        width: 80%;
        border-radius: 25px;
    }

    .minor {
      font-size: 110px;
      font-weight: normal;
      font-family: monospace;
      color: white;
    }
    
    .major {
      font-size: 130px;
      font-weight: 700px;
      font-family: monospace;
      color: white;
    }

    .toptoptext {
        text-align: center;
    }

    .topmiddletext {
        text-align: center;
    }


</style>












