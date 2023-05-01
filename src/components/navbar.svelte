<script>

export let pagetitle;

</script>

<body>

    <div class="topnav">
        <a href="/">Home</a>
        <!-- svelte-ignore a11y-invalid-attribute -->
        <a href="/browsers">Browsers</a>
        <!-- svelte-ignore a11y-invalid-attribute -->
        <a href="/aboutus">About Us</a>
    </div>

    <title class = "title">{pagetitle}</title>

</body>

<style>

    body {
        font-family: monospace;
        margin: 0;
    }

    .topnav {
      overflow: hidden;
      background-color: #333;
      position: sticky;
      top: 0px;
    }
    
    /* Style the topnav links */
    .topnav a {
      float: left;
      display: block;
      color: #FAE6FA;
      text-align: center;
      padding: 14px 16px;
      text-decoration: none;
    }
    
    /* Change color on hover */
    .topnav a:hover {
      background-color: #ddd;
      color: black;
    }

</style>