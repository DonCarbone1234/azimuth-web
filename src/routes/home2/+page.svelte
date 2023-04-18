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

    .toptext1 {
        text-align: center;
    }

    .middletext1 {
        text-align: center;
    }

    .minor {
      font-size: 75px;
      font-weight: normal;
      font-family: monospace;
      color: white;
    }
    
    .major {
      font-size: 100px;
      font-weight: bold;
      font-family: monospace;
      color: white;
    }
    
    body {
        font-family: monospace;
        margin: 0;
    }
    
    .testflex {
      display: flex;
      align-items: center;
      background-color: #4d526a;
      background-image: url(blue4small.svg);
      background-size: cover;
      background-attachment: fixed;
     /* background-repeat: no-repeat; */
     /* background-position: center; */
      align-content: center;
      flex-direction: column;
      flex-wrap: nowrap;
      padding: 120px 0px;
      z-index: 5;
    }
    
    .textbackground {
        background-color: #4d526a;
        padding: 50px 60px;
        max-width: 650px;
        width: 80%;
    }





    .flexbox2 {
    background-color: #1e1e1e;
    background-image: url(whitemini1.svg);
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
    }

    .majorwhite {
        color: #111;
        font-size: 45px;
        font-weight: 700;
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

    </style>
    
    
    <body>
        <div class="topnav">
            <a href="/home">Home</a>
            <!-- svelte-ignore a11y-invalid-attribute -->
            <a href="#">Games</a>
            <!-- svelte-ignore a11y-invalid-attribute -->
            <a href="#">About Us</a>
        </div>
    
        <div class="testflex">
            <div class= "textbackground">
                <div class="toptext1">
                 <p>
                <span class="minor">Welcome to</span>
                <br>
                <span class="major">Azimuth</span>
                 </p>
    
              </div>
    
                 <div class="middletext1">
                     <p style="color: white; font-size: 30px; font-wieght: normal;">
                         Azimuth makes game streaming easy. We use a decentralized network to stream games to and from your pc, all while guraenteeying safety and high quality.
                     </p>
                 </div>
    
            </div>
        </div>

        <div class="flexbox2">

            <div class="whitetextbackground">

                <div class="middlebox1">
                    <div class="topmiddlebox1">
                        <h1> <span class="majorwhite">How does Azimuth work?</span></h1>
                    </div>
                    <p><span class="minorwhite">placeholder text</span></p>
                </div>

                <div class="leftbox1">
                    <div class = "image1">
                        <img src = "blackplaceholder.png" alt = "placeholder">
                    </div>
                    <div class="topleftbox1">
                        <h1> <span class="majorwhite">placeholder</span></h1>
                        <p><span class="minorwhite"> placeholder text</span></p>
                    </div>
                    
                </div>
            
                <div class="rightbox1">
                    <div class="toprightbox1">
                        <h1> <span class="majorwhite">placeholder</span></h1>
                        <p><span class="minorwhite"> placeholder text</span></p>
                    </div>
                    <div class = "image2">
                        <img src = "blackplaceholder.png" alt = "placeholder">
                    </div>
                </div>
            </div>
        </div>
    
    </body>

   
    