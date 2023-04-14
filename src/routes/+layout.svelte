
<style>
    * {
      box-sizing: border-box;
      font-family: Arial, Helvetica, sans-serif;
    }
    
    body {
      margin: 0;
      font-family: Arial, Helvetica, sans-serif;
    }
    
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
    
    /* Style the content */
    .content {
      background-color: #3c0052;
      color: #3c0052;
      padding: 10px;
      object-fit: fill;
      height: fit-content;
      /*
      max-width:100%;  
      overflow-x: scroll;
      */
    } 
    
    /* Style the footer */
    .footer {
      background-color: #240032;
      color: #FAE6FA;
      padding: 0px;
      width: 100%;
      text-align:center;
      border-top: solid 1px #FAE6FA;
      padding-bottom: 1px;
      font-size: 25px;
    }
    </style>

<body>

    <div class="topnav">
      <a href="/home">Home</a>
      <a href="#">Games</a>
      <a href="#">About Us</a>
    </div>
    
    <div class="content">
     <slot>
        
     </slot>
    </div>
    
   
    
    <div class="footer">
      <p>azimuth</p>
    </div>
  
    </body>