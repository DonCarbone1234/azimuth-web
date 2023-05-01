<script>
    import Bluebox from "../components/bluebox.svelte";
    import Navbar from "../components/navbar.svelte";
    import Orangebox from "../components/orangebox.svelte";
    import Footer from "../components/footer.svelte";
    import Whiteboxblank from "../components/whiteboxblank.svelte";
    import Leftrow from "../components/leftrow.svelte";
    import Rightrow from "../components/rightrow.svelte";
    import Titleanddesc from "../components/titleanddesc.svelte";
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
        middletext = 'Azimuth makes secure browsing easy. We use a decentralized network to stream a browser of your choice to your pc, all while guaranteeing safety and high quality.'
        
        />


        <Whiteboxblank>

            <Titleanddesc
                titletext = "How does Azimuth work?"
                desctext = "We use a combination of docker containers and our own code to stream a perfect browsing experience to you!"
            />

            <Leftrow
                leftalttext = "placeholder"
                leftimage = "blackplaceholder.png"
                leftdesc = "Placeholder Text"
                lefttitle = "Placeholder"
            />

            <Rightrow 
                rightalttext = "placeholder"
                rightimage = "blackplaceholder.png"
                rightdesc = "Placeholder Text"
                righttitle = "Placeholder"
            />

        </Whiteboxblank>

        <Orangebox
        toptitle = 'Try it out!'
        middledesc = 'Click Here'
        />

        <Footer

        />

</body>


