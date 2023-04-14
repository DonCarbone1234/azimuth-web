<script>
    let left;

    const handleMove = (e) => {
        // console.log("test");
        left.style.width = `${(e.clientX / window.innerWidth) * 100}%`;
    };

    // document.addEventListener("mousemove", handleMove);
</script>

<!-- svelte-ignore a11y-missing-attribute -->
<html lang="en" on:mousemove={handleMove}>
    <head>
        <meta charset="UTF-8" />
        <title>Home</title>
        <link rel="preconnect" href="https://fonts.googleapis.com" />
        <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
        <link
            href="https://fonts.googleapis.com/css2?family=Lobster&family=Rubik:wght@400;500&display=swap"
            rel="stylesheet"
        /><link rel="stylesheet" href="./style.css" />
    </head>
    <body>
        <!-- partial:index.partial.html -->
        <div class="content">
            <div id="left-side" bind:this={left} class="side">
                <h2 class="title">
                    Streaming Games     
                    <span class="fancy">made easy</span>
                </h2>
            </div>
            <div id="right-side" class="side">
                <h2 class="title">
                    Streaming Games     
                    <span class="fancy">made easy</span>
                </h2>
            </div>
        </div></body
    >
</html>

<style>
    :root {
        --dark: rgb(20, 20, 20);
        --yellow: rgb(253, 216, 53);
        --blue: rgb(98, 0, 234);

        --c1: rgb(217, 0, 119);
        --c2: rgb(65, 17, 84);

        --left-color: var(--c1);
        --right-color: var(--c2);
    }

    body {
        background-color: var(--dark);
        margin: 0px;
    }

    .side {
        display: grid;
        height: 100vh;
        overflow: hidden;
        place-items: center;
        position: absolute;
        width: 100vw;
    }

    .side .title {
        font-family: "Rubik", sans-serif;
        font-size: 8vw;
        margin: 0px 15vw;
        width: 80vw;
    }

    .side .fancy {
        font-family: "Lobster", cursive;
        font-size: 1.3em;
        line-height: 0.8em;
        margin: 0px 12vw;
    }

    #left-side {
        background-color: var(--left-color);
        width: 60%;
        z-index: 2;
    }

    #left-side .title {
        color: #008ECC;
    }

    #left-side .fancy {
        color: var(--right-color);
        text-align: center;
    }

    #right-side {
        background-color: var(--right-color);
    }

    #right-side .title {
        color: #008ECC;
        /*var(--dark)*/
    }

    #right-side .fancy {
        color: #d90077;
        text-align: center;
    }
</style>
