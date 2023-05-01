<script>

    export let toptitle;
    export let topdesc;
    export let middletext;

</script>

<body>

    <div class="testflex">
        <div class= "textbackground">
            <div class="toptext1">
                <p>
                    <span class="minor">{toptitle}</span>
                    <br>
                    <span class="major">{topdesc}</span>
                </p>

          </div>

             <div class="middletext1">
                 <p style="color: white; font-size: 30px; font-wieght: normal;">
                     {middletext}
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

    .testflex {
      display: flex;
      align-items: center;
      background-color: #4d526a;
      background-image: url('https://raw.githubusercontent.com/DonCarbone1234/azimuth-web/main/static/blue4small.svg');
      background-size: cover;
      background-attachment: fixed;
      align-content: center;
      flex-direction: column;
      flex-wrap: nowrap;
      padding: 120px 0px;
      z-index: 5;
    }
    
    .textbackground {
        background-color: #383e59ff;
        padding: 50px 60px;
        max-width: 1100px;
        width: 80%;
        border-radius: 25px;
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


</style>