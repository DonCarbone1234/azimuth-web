<script>

    export let toptitle;
    export let middledesc;

</script>

<body>

    <div class="orangetextbox">

        <div class="orangebackground">

            <div class="orangetitle">
                <p>
                    <span class="major">{toptitle}</span>
                </p>
            </div>
               
            <div class="orangedescription">
                 <p style="color: white; font-size: 30px; font-wieght: normal;">
                    {middledesc}
                </p>
            </div>

        </div>

    </div>

</body>

<style>

    body {
        font-family: monospace;
        margin: 0;
    }

    .orangetextbox {
    background-color: #111;
    background-image: url('https://raw.githubusercontent.com/DonCarbone1234/azimuth-web/main/static/orange-1-mini.svg');
    background-size: cover;
    background-attachment: fixed;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-content: center;
    align-items: center;
    flex-wrap: nowrap;
    padding: 120px 0px;
    z-index: 5;
    }

    .orangebackground {
        background-color: #ff9b01;
        padding: 50px 60px;
        max-width: 650px;
        width: 80%;
        border-radius: 25px;
    }

    .major {
      font-size: 100px;
      font-weight: bold;
      font-family: monospace;
      color: white;
    }

</style>




