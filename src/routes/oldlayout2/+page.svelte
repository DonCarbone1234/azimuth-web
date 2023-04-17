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
  
  .minor {
    font-size: 20px;
    font-weight: normal;
    font-family: monospace;
    color: white;
  }
  
  .major {
    font-size: 35px;
    font-weight: bold;
    font-family: monospace;
    color: white;
  }
  
  body {
    font-family: monospace;
    color: white;
  }
  
  .testflex {
    display: flex;
    align-items: center;
    background-color: #283780;
    background-image: url(https://cdn.akamai.steamstatic.com/apps/csgo/images/csgo_react/cs2/bgDarkBlue.svg);
    background-size: cover;
    background-attachment: fixed;
    align-content: center;
    flex-direction: column;
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
                   <h1>
                       Azimuth makes game streaming easy. We use a decentralized network to stream games to and from your pc, all while guraenteeying safety and high quality.
                   </h1>
               </div>
  
          </div>
      </div>
  
  </body>
  