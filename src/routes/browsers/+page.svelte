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
    }

    .chrome:hover{
        background-color:#D3D3D3;
    }

    .edge{
        background-color:#fff;
        padding: 50px 50px;
        width: 20%;
        border-radius: 25px;
        line-height: 50px;
        padding-bottom: 15px;
    }

    .edge:hover{
        background-color:#D3D3D3;
    }

    .firefox{
        background-color:#fff;
        padding: 50px 50px;
        width: 20%;
        border-radius: 25px;
        line-height: 50px;
        padding-bottom: 15px;
    }

    .firefox:hover{
        background-color:#D3D3D3;
    }

    .brave{
        background-color:#fff;
        padding: 50px 50px;
        width: 20%;
        border-radius: 25px;
        line-height: 50px;
        padding-bottom: 15px;
    }

    .brave:hover {
        background-color:#D3D3D3;
    }

    .tor{
        background-color:#fff;
        padding: 50px 50px;
        width: 20%;
        border-radius: 25px;
        line-height: 50px;
        padding-bottom: 15px;
    }

    .tor:hover{
        background-color:#D3D3D3;
    }

    .retroarch{
        background-color:#fff;
        padding: 50px 50px;
        width: 20%;
        border-radius: 25px;
        line-height: 50px;
        padding-bottom: 15px;
    }

    .retroarch:hover {
        background-color:#D3D3D3;
    }

</style>

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

                <div class="chrome">
                    <a href="chrome" style="text-decoration:none;">
                        <img class="resizeimage" src = "chromelogo.png" alt = "chrome logo">
                        <p><span class="boxtext">Chrome</span></p>
                      </a>
                </div>

                <div class="edge">
                    <a href="edge" style="text-decoration:none;">
                        <img class="resizeimage" src = "Microsoft_Edge_logo_(2019).png" alt = "Edge logo">
                        <p><span class="boxtext">Edge</span></p>
                      </a>
                </div>

                <div class="firefox">
                    <a href="firefox" style="text-decoration:none;">
                        <img class="resizeimage" src = "Firefox_logo,_2017.png" alt = "FireFox logo">
                        <p><span class="boxtext">Firefox</span></p>
                      </a>
                </div>

                <div class="brave">
                    <a href="brave" style="text-decoration:none;">
                        <img class="resizeimage" src = "Brave_icon_lionface.png" alt = "Brave logo">
                        <p><span class="boxtext">Brave</span></p>
                      </a>
                </div>

                <div class="tor">
                    <a href="tor" style="text-decoration:none;">
                        <img class="resizeimage" src = "tortransparent1.png" alt = "Tor logo">
                        <p><span class="boxtext">Tor</span></p>
                      </a>
                </div>

                <div class="retroarch">
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

