<script>

    export let linkto;
    export let browserlogo;
    export let alttext;
    export let browsername;

</script>

<body>

     <!-- svelte-ignore a11y-missing-attribute -->
     <a href = {linkto}>
        <div class="browser">
            <img class="resizeimage" src = {browserlogo} alt = {alttext}>
            <p><span class="boxtext">{browsername}</span></p>
        </div>
    </a>
</body>

<style>

    body {
        font-family: monospace;
        margin: 0;
        text-decoration:none;
    }

    .boxtext {
        text-decoration:none;
        text-align: center;
        color: #333;
        font-size: 25px;
    }

    .resizeimage{
        max-width: 200px;
        max-height: 200px;
    }

    .browser{
        background-color:#fff;
        padding: 50px 50px 15px;
        border-radius: 25px;
        line-height: 50px;
        padding-bottom: 15px;
        transition-duration: 0.5s;
        cursor: pointer;
        width: 272.8px;
        display: flex;
        flex-direction: column;
        align-content: center;
        align-items: center;
        align-self: center;
    }

    .browser:hover{
        background-color:#D3D3D3;
        transition-duration: 0.5s;
    }

</style>





