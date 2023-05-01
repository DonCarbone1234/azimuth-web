<script>



</script>

<body>

    <div class="browserboxes"> 
        <slot>

        </slot>
    </div>

</body>

<style>

    body {
        font-family: monospace;
        margin: 0;
    }

    .browserboxes {
        display: flex;
        flex-wrap: wrap;
        flex-direction: row;
        justify-content: space-evenly;
        align-content: center;
        align-items: center;
        padding: 40px 80px;
        gap: 50px;
    }

</style>







