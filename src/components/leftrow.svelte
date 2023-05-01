<script>

export let leftimage;
export let leftalttext;
export let lefttitle;
export let leftdesc;

</script>



    <div class="leftbox1">
        <div class = "image1">
            <!-- svelte-ignore a11y-img-redundant-alt -->
            <img class ="resizeimage" src = "{leftimage}" alt = "{leftalttext}">
        </div>
        <div class="topleftbox1">
            <h1> <span class="majorwhite">{lefttitle}</span></h1>
            <p><span class="minorwhite">{leftdesc}</span></p>
        </div>
        
    </div>


<style>

    .minorwhite {
        color: #111;
        font-size: 25px;
        text-align: left;
    }

    .majorwhite {
        color: #111;
        font-size: 45px;
        font-weight: 700;
        text-align: left;
    }

    .image1 {
        padding-right: 50px;
    }

    .leftbox1 {
        display: flex;
        flex-direction: row;
        justify-content: left;
        align-content: center;
        padding-bottom: 25px;
    }

    .topleftbox1 {
        text-align: left;
    }

    .resizeimage{
        width: max-content;
        max-width: 400px;
        max-height: auto;
        border-radius: 25px;
    }

</style>




