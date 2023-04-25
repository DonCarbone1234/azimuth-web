<style>
.topnav {
      overflow: hidden;
      background-color: #333;
    }
    
    /* Style the topnav links */
    .topnav a {
      float: left;
      display: block;
      color: #FAE6FA;
      text-align: center;
      padding: 14px 16px;
      text-decoration: none;
    }
    
    /* Change color on hover */
    .topnav a:hover {
      background-color: #ddd;
      color: black;
    }

    body {
        font-family: monospace;
        margin: 0;
    }
    
    .footer {
        display: flex;
        width: 100%;
        height: fit-content;
        background-color:#240032ff;
        align-items: center;
        flex-direction: column;  
        border-top-style: solid;
        border-top-color: #d394ff;
        overflow: hidden;
    }

    .footercontent {
        font-size: 20px;
        color:#d394ff;
    }

    .toptext {
        font-size: 125px;
        font-weight: 700;
        text-align: center;
        color:#333;
    }

    .toptextbox{
        padding: 25px 25px;
    }

    .boxtext {
        text-decoration:none;
        text-align: center;
        color: #333;
        font-size: 25px;
    }

    .mainflexbox {
        background-repeat: no-repeat;
        background-image: url("orange-1-mini.svg");
        background-attachment: fixed;
        background-size: cover;
        display: flex;
        flex-wrap: nowrap;
        flex-direction: column;
        /*justify-content: space-evenly;*/
        align-content: center;
        align-items: center; 
        padding: 120px 0px;
    }

    .resizeimage{
        max-width: 200px;
        max-height: 200px;
    }

    .mainbackground {
        background-color: #eee;
        width: 80%;
        text-align: center;
        border-radius: 25px;
        display: flex;
        flex-wrap: nowrap;
        flex-direction: column;
        /* justify-content: space-evenly; */
        align-content: center;
        align-items: center; 
        padding: 80px 0px;
    }

    .browserboxes {
        display: flex;
        flex-wrap: wrap;
        flex-direction: row;
        justify-content: space-evenly;
        align-content: center;
        align-items: center;
        padding: 40px 80px;
        gap: 50px;
    }

    .chrome{
        background-color:#fff;
        padding: 50px 50px;
        width: 20%;
        border-radius: 25px;
        line-height: 50px;
        padding-bottom: 15px;
        transition-duration: 0.5s;
        cursor: pointer;
    }

    .chrome:hover{
        background-color:#D3D3D3;
        transition-duration: 0.5s;
    }

    .edge{
        background-color:#fff;
        padding: 50px 50px;
        width: 20%;
        border-radius: 25px;
        line-height: 50px;
        padding-bottom: 15px;
        transition-duration: 0.5s;
        cursor: pointer;
    }

    .edge:hover{
        background-color:#D3D3D3;
        transition-duration: 0.5s;
    }

    .firefox{
        background-color:#fff;
        padding: 50px 50px;
        width: 20%;
        border-radius: 25px;
        line-height: 50px;
        padding-bottom: 15px;
        transition-duration: 0.5s;
        cursor: pointer;
    }

    .firefox:hover{
        background-color:#D3D3D3;
        transition-duration: 0.5s;
    }

    .brave{
        background-color:#fff;
        padding: 50px 50px;
        width: 20%;
        border-radius: 25px;
        line-height: 50px;
        padding-bottom: 15px;
        transition-duration: 0.5s;
        cursor: pointer;
    }

    .brave:hover {
        background-color:#D3D3D3;
        transition-duration: 0.5s;
    }

    .tor{
        background-color:#fff;
        padding: 50px 50px;
        width: 20%;
        border-radius: 25px;
        line-height: 50px;
        padding-bottom: 15px;
        transition-duration: 0.5s;
        cursor: pointer;
    }

    .tor:hover{
        background-color:#D3D3D3;
        transition-duration: 0.5s;
    }

    .retroarch{
        background-color:#fff;
        padding: 50px 50px;
        width: 20%;
        border-radius: 25px;
        line-height: 50px;
        padding-bottom: 15px;
        transition-duration: 0.5s;
        cursor: pointer;
    }

    .retroarch:hover {
        background-color:#D3D3D3;
        transition-duration: 0.5s;
    }

</style>

<script lang="ts">
    function routeTo(loc) {
        window.location.href = loc;
    }
</script>

<body>

    <title>Browsers</title>

    <div class="topnav">

        <a href="/home2">Home</a>
        <!-- svelte-ignore a11y-invalid-attribute -->
        <a href="/browsers">Browsers</a>
        <!-- svelte-ignore a11y-invalid-attribute -->
        <a href="/aboutus">About Us</a>

    </div>

    <div class="mainflexbox">

        <div class="mainbackground">

            <div class="toptextbox">
                <p><span class="toptext">Browser Launch</span></p>
            </div>
        
            <div class="browserboxes">

                <!-- svelte-ignore a11y-click-events-have-key-events -->
                <div class="chrome" on:click={() => routeTo("/chrome")}>
                        <img class="resizeimage" src = "chromelogo.png" alt = "chrome logo">
                        <p><span class="boxtext">Chrome</span></p>
                </div>

                <!-- svelte-ignore a11y-click-events-have-key-events -->
                <div class="edge" on:click={() => routeTo("/edge")}>
                    <img class="resizeimage" src = "Microsoft_Edge_logo_(2019).png" alt = "Edge logo">
                    <p><span class="boxtext">Edge</span></p>
                </div>

                <!-- svelte-ignore a11y-click-events-have-key-events -->
                <div class="firefox" on:click={() => routeTo("/firefox")}>
                    <a href="firefox" style="text-decoration:none;">
                        <img class="resizeimage" src = "Firefox_logo,_2017.png" alt = "FireFox logo">
                        <p><span class="boxtext">Firefox</span></p>
                      </a>
                </div>

                <!-- svelte-ignore a11y-click-events-have-key-events -->
                <div class="brave" on:click={() => routeTo("/brave")}>
                    <a href="brave" style="text-decoration:none;">
                        <img class="resizeimage" src = "Brave_icon_lionface.png" alt = "Brave logo">
                        <p><span class="boxtext">Brave</span></p>
                      </a>
                </div>

                <!-- svelte-ignore a11y-click-events-have-key-events -->
                <div class="tor" on:click={() => routeTo("/tor")}>
                    <a href="tor" style="text-decoration:none;">
                        <img class="resizeimage" src = "tortransparent1.png" alt = "Tor logo">
                        <p><span class="boxtext">Tor</span></p>
                      </a>
                </div>

                <!-- svelte-ignore a11y-click-events-have-key-events -->
                <div class="retroarch" on:click={() => routeTo("/retroarch")}>
                    <a href="retroarch" style="text-decoration:none;">
                        <img class="resizeimage" src = "Retroarch2png.png" alt = "retroarch logo">
                        <p><span class="boxtext">RetroArch</span></p>
                      </a>
                </div>

            </div>

        </div>

    </div>






    <div class="footer">
            
        <p><span class="footercontent">azimuth</span></p>
    
    </div>

</body>

