<style>
/* Style the top navigation bar */
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

    body {
        margin: 0;
        font-family: monospace;
    }

    .topflexbox {
        background-image: url("blue4small.svg");
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
      font-size: 75px;
      font-weight: normal;
      font-family: monospace;
      color: white;
    }
    
    .major {
      font-size: 100px;
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

<body>

    <title>About Us</title>

    <div class="topnav">
        <a href="/home2">Home</a>
        <!-- svelte-ignore a11y-invalid-attribute -->
        <a href="/browsers">Browsers</a>
        <!-- svelte-ignore a11y-invalid-attribute -->
        <a href="/aboutus">About Us</a>
    </div>

    <div class="topflexbox">

        <div class="toptextbackground">

            <div class="toptoptext">
                <span class="minor">About</span>
                <br>
                <span class="major">Us</span>
            </div>

            <div class="topmiddletext">
                <p style="color: white; font-size: 30px; font-wieght: normal;">The team behind Azimuth</p>
            </div>

        </div>

    </div>

      
    <div class="footer">
            
        <p><span class="footercontent">azimuth</span></p>
    
    </div>

</body>