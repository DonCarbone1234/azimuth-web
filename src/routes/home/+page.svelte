<style>
    :root {
  --dark: rgb(20, 20, 20);
  --yellow: rgb(253, 216, 53);
  --blue: rgb(98, 0, 234);
  
  --c1: rgb(251, 32, 255);
  --c2: rgb(235, 138, 255);
  
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
  width: 100%;
}

.side .title {
  font-family: "Rubik", sans-serif;
  font-size: 8vw;
  margin: 0px 10vw;
  width: 80vw;
}

.side .fancy {
  font-family: "Lobster", cursive;
  font-size: 1.3em;
  line-height: 0.8em;
}

#left-side {
  background-color: var(--left-color);
  width: 60%;
  z-index: 2;
}

#left-side .title {  
  color: #d394ff;  
}

#left-side .fancy {
  color: var(--right-color);
}

#right-side {
  background-color: var(--right-color);
}

#right-side .title {
  color: var(--dark);
}

#right-side .fancy {
  color: #d394ff;
}
</style>

<script>
    const left = document.getElementById("left-side");

const handleMove = e => {
  left.style.width = `${e.clientX / window.innerWidth * 100}%`;
}

document.onmousemove = e => handleMove(e);

document.ontouchmove = e => handleMove(e.touches[0]);
</script>
    
    <!-- svelte-ignore a11y-missing-attribute -->
    <html lang="en" >
<head>
  <meta charset="UTF-8">
  <title>CodePen - Super Header Slider</title>
  <link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Lobster&family=Rubik:wght@400;500&display=swap" rel="stylesheet"><link rel="stylesheet" href="./style.css">

</head>
<body>
<!-- partial:index.partial.html -->
<div class = content>
<div id="left-side" class="side">
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


</body>
</html>