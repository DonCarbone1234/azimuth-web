<script>
    import Bluebox from "../components/bluebox.svelte";
    import Navbar from "../components/navbar.svelte";
    import Whitebox from "../components/whitebox.svelte";
    import Orangebox from "../components/orangebox.svelte";
    import Footer from "../components/footer.svelte";
</script>

<style>

    body {  
        font-family: monospace;
        margin: 0;
    }

</style>
    
    
<body>

        <Navbar

        pagetitle = 'Home'

        />

        <Bluebox

        toptitle = 'Welcome to'
        topdesc = 'Azimuth'
        middletext = 'Azimuth makes game secure browsing easy. We use a decentralized network to stream a browser of your choice to your pc, all while guaranteeing safety and high quality.'
        
        />

        <Whitebox
        toptitle2 = 'How does Azimuth work?'
        topdesc2 = 'Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.'
        lefttitle = 'Placeholder'
        leftdesc = 'Placeholder Text'
        leftimage = 'blackplaceholder.png'
        leftalttext = 'placeholder'
        righttitle = 'Placeholder'
        rightdesc = 'Placeholdertext'
        rightimage = 'blackplaceholder.png'
        rightalttext = 'placeholder'
        />
       
        <Orangebox
        toptitle = 'Placeholder'
        middledesc = 'Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.'
        />

        <Whitebox
        toptitle2 = 'How does Azimuth work?'
        topdesc2 = 'Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.'
        lefttitle = 'Placeholder'
        leftdesc = 'Placeholder Text'
        leftimage = 'blackplaceholder.png'
        leftalttext = 'placeholder'
        righttitle = 'Placeholder'
        rightdesc = 'Placeholdertext'
        rightimage = 'blackplaceholder.png'
        rightalttext = 'placeholder'
        />
    
        <Footer

        />

</body>


