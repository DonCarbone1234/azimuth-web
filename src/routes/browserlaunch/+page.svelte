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
        font-size: 75px;
        font-weight: 700;
        text-align: center;
        color:#333;
    }

    .boxtext {
        text-align: center;
        color: #333;
        font-size: 25px;
    }

    .mainflexbox {
        display: flex;
        flex-wrap: nowrap;
        flex-direction: column;
        background-repeat: no-repeat;
        background-image: url("orange-1-mini.svg");
        background-attachment: fixed;
        background-size: cover;
        justify-content: center;
        align-content: center;
        align-items: center;
        padding: 120px 0px;
    }

    .resizeimage{
        width: 200px;
        height: auto;
    }

    .mainbackground {
        background-color: #eee;
        width: 80%;
        text-align: center;
    }

    .chrome{
        background-color:#fff;
        
    }

</style>

<body>

    <div class="topnav">

        <a href="/home">Home</a>
        <!-- svelte-ignore a11y-invalid-attribute -->
        <a href="/browserlaunch">Browsers</a>
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
                    <img class="resizeimage" src = "chromelogo.png" alt = "chrome logo">
                    <p><span class="boxtext">Chrome</span></p>
                </div>

                <div class="edge">
                    <img class="resizeimage" src = "Microsoft_Edge_logo_(2019).png" alt = "Edge logo">
                    <p><span class="boxtext">Edge</span></p>
                </div>

                <div class="firefox">
                    <img class="resizeimage" src = "Firefox_logo,_2017.png" alt = "FireFox logo">
                    <p><span class="boxtext">Firefox</span></p>
                </div>

                <div class="brave">
                    <img class="resizeimage" src = "Brave_icon_lionface.png" alt = "Brave logo">
                    <p><span class="boxtext">Brave</span></p>
                </div>

                <div class="tor">
                    <img class="resizeimage" src = "Tor_logo1.png" alt = "Tor logo">
                    <p><span class="boxtext">Tor</span></p>
                </div>

                <div class="retroarch">
                    <img class="resizeimage" src = "Retroarch2png.png" alt = "retroarch logo">
                    <p><span class="boxtext">RetroArch</span></p>
                </div>

            </div>

        </div>

    </div>






    <div class="footer">
            
        <p><span class="footercontent">azimuth</span></p>
    
    </div>

</body>

