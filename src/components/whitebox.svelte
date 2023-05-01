<script>

export let toptitle2;
export let topdesc2;
export let lefttitle;
export let leftdesc;
export let leftimage;
export let leftalttext;
export let righttitle;
export let rightdesc;
export let rightimage;
export let rightalttext;

</script>

<body>

    <div class="flexbox2">

        <div class="whitetextbackground">

            <div class="middlebox1">
                <div class="topmiddlebox1">
                    <h1> <span class="majorwhite">{toptitle2}</span></h1>
                </div>
                <p><span class="minorwhite">{topdesc2}</span></p>
            </div>

            <div class="leftbox1">
                <div class = "image1">
                    <img src = "{leftimage}" alt = "{leftalttext}">
                </div>
                <div class="topleftbox1">
                    <h1> <span class="majorwhite">{lefttitle}</span></h1>
                    <p><span class="minorwhite">{leftdesc}</span></p>
                </div>
                
            </div>
        
            <div class="rightbox1">
                <div class="toprightbox1">
                    <h1> <span class="majorwhite">{righttitle}</span></h1>
                    <p><span class="minorwhite">{rightdesc}</span></p>
                </div>
                <div class = "image2">
                    <img src = "{rightimage}" alt = "{rightalttext}">
                </div>
            </div>
        </div>
    </div>


</body>

<style>

    body {
        font-family: monospace;
        margin: 0;
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
        border-radius: 25px;
    }

    .image2 {
        padding-right: 50px;
        padding-left: 50px;
        border-radius: 25px;
    }

    .rightbox1 {
        display: flex;
        flex-direction: row;
        justify-content: right;
        align-content: center;
        
    }

    .topmiddlebox1 {
        text-align: center;
    }

    .topleftbox1 {
        text-align: center;
    }

    .toprightbox1 {
        text-align: center;
    }

</style>


