<script>
    
</script>
    
<body>
    
    <div class="flexbox2">
    
        <div class="orangetextbackground">  
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
        background-image: url('https://raw.githubusercontent.com/DonCarbone1234/azimuth-web/main/static/orange-1-mini.svg');
        background-size: cover;
        background-attachment: fixed;
        display: flex;
        flex-direction: column;
        justify-content: center;
        align-content: center;
        align-items: center;
        flex-wrap: nowrap;
        padding: 80px 0px;
        z-index: 5;
        
        }

        .orangetextbackground {
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
        padding-bottom: 80px;
        }
    
</style>
    
    
    
    
    
    
    
    
    
    
    
    
    