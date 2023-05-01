<script>

export let rightimage;
export let rightalttext;
export let righttitle;
export let rightdesc;

</script>

<body>

<div class="rightbox1">
                <div class="toprightbox1">
                    <h1> <span class="majorwhite">{righttitle}</span></h1>
                    <p><span class="minorwhite">{rightdesc}</span></p>
                </div>
                <div class = "image2">
                    <img class ="resizeimage" src = "{rightimage}" alt = "{rightalttext}">
                </div>
            </div>

</body>

<style>

    
    .minorwhite {
        color: #111;
        font-size: 25px;
        text-align: right;
    }

    .majorwhite {
        color: #111;
        font-size: 45px;
        font-weight: 700;
        text-align: right;
    }


    body {
        margin: 0;
        font-family: monospace;
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
        padding-bottom: 25px;
    }

    .toprightbox1 {
        text-align: center;
    }

    .resizeimage{
        width: max-content;
        max-width: 400px;
        max-height: auto;
        border-radius: 25px;
    }


</style>






