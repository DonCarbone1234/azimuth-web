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
                <a href="/browsers">
                    <button class = "button1">
                        <p style="color:#434343ff; font-size: 60px; font-wieght: normal;">
                            {middledesc}
                        </p>
                    </button>
                </a>
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
        max-width: 1100px;
        width: 80%;
        border-radius: 25px;
        text-align: center;
        display: flex;
        flex-direction: column;
        align-items: center;
        gap: 50px;
    }

    .major {
      font-size: 100px;
      font-weight: bold;
      font-family: monospace;
      color: white;
    }

    .button1 {
        border-width: 0px;
        border-radius: 25px;
        font-family: monospace;
        height: 200px;
        width: 400px;
        transition-duration: 0.5s;
    }

    .button1:hover{
        background-color:#D3D3D3;
        transition-duration: 0.5s;
    }

</style>




