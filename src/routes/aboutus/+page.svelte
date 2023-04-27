<style>
.topnav {
      overflow: hidden;
      background-color: #333;
    }
    
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

    .flexbox2 {
    background-color: #1e1e1e;
    background-image: url('https://raw.githubusercontent.com/DonCarbone1234/azimuth-web/main/static/whitemini1.svg');
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

    .topmiddlebox1 {
        text-align: center;
    }

    .middlebox1 {
        padding-top: 50px;
        padding-bottom: 100px;
    }

    .whitetextbackground {
        background-color: #eee;
        padding: 50px 60px;
        max-width: 650px;
        width: 80%;
        max-width: 1100px;
        width: 100%;
        border-radius: 25px;
    }

    .majorwhite {
        color: #111;
        font-size: 45px;
        font-weight: 700;
        text-align: center;
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

    .leftbox1 {
        display: flex;
        flex-direction: row;
        justify-content: left;
        align-content: center;
    }

    .image1 {
        padding-right: 50px;
    }

    .image2 {
        padding-right: 50px;
        padding-left: 50px;
    }

    .rightbox1 {
        display: flex;
        flex-direction: row;
        justify-content: right;
        align-content: center;
        
    }

    .resizeimage{
        max-width: 400px;
        max-height: auto;
        border-radius: 25px;
    }

    .milesresizeimage{
        max-width: auto;
        max-height: 400px;
        border-radius: 25px;
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
                <p style="color: white; font-size: 40px; font-wieght: normal;">The team behind Azimuth</p>
            </div>

        </div>

    </div>

    <div class="flexbox2">

        <div class="whitetextbackground">

            <div class="middlebox1">
                <div class="topmiddlebox1">
                    <h1> <span class="majormajorwhite">Meet the members</span></h1>
                </div>
                <p><span class="minorwhite"></span></p>
            </div>

            <div class="leftbox1">
                <div class = "image1">
                    <img class ="resizeimage" src = "blackplaceholder.png" alt = "placeholder">
                </div>
                <div class="topleftbox1">
                    <h1> <span class="majorwhite">Jeremy</span></h1>
                    <p><span class="minorwhite"> Website Developer</span></p>
                </div>
                
            </div>
        
            <div class="rightbox1">
                <div class="toprightbox1">
                    <h1> <span class="majorwhite">Nicholas</span></h1>
                    <p><span class="minorwhite"> Lead Backend Developer <br> Architect</span></p>
                </div>
                <div class = "image2">
                    <img class ="resizeimage" src = "blackplaceholder.png" alt = "placeholder">
                </div>
            </div>

            
            <div class="leftbox1">
                <div class = "image1">
                    <!-- svelte-ignore a11y-img-redundant-alt -->
                    <img class ="milesresizeimage" src = "skinwalkermiles.png" alt = "A picture of Miles but he looks like a skinwalker">
                </div>
                <div class="topleftbox1">
                    <h1> <span class="majorwhite">Miles</span></h1>
                    <p><span class="minorwhite"> Assistant Developer <br> Assistant Architect</span></p>
                </div>
                
            </div>

            <div class="rightbox1">
                <div class="toprightbox1">
                    <h1> <span class="majorwhite">Ben</span></h1>
                    <p><span class="minorwhite"> Marketing <br> Quality Assurance</span></p>
                </div>
                <div class = "image2">
                    <!-- svelte-ignore a11y-img-redundant-alt -->
                    <img class ="resizeimage" src = "benwithcat.png" alt = "A picture of Ben with his cat">
                </div>
            </div>

        </div>
    </div>



      
    <div class="footer">
            
        <p><span class="footercontent">azimuth</span></p>
    
    </div>

</body>