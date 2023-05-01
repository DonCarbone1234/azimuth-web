<script>
    
</script>
    
<body>
    
    <div class="flexbox2">
    
        <div class="whitetextbackground">  
                <slot>



                </slot>
        </div>
    </div>
    
</body>
    
<style>
    
    body {
            margin: 0;
            font-family: monospace;
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
        .whitetextbackground {
            background-color: #eee;
            padding: 50px 60px;
            width: 80%;
            max-width: 1100px;
            width: 100%;
            border-radius: 25px;
        }
    
</style>
    
    
    
    
    
    
    
    
    
    
    
    
    