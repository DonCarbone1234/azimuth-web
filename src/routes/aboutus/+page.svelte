<script>   
    import Bluebox2 from "../../components/bluebox2.svelte";
    import Navbar from "../../components/navbar.svelte";
    import Whiteboxblank from "../../components/whiteboxblank.svelte";
    import Leftrow from "../../components/leftrow.svelte";
    import Rightrow from "../../components/rightrow.svelte";
    import Footer from "../../components/footer.svelte";
    import Title from "../../components/title.svelte";
</script>

<style>

    body {
        margin: 0;
        font-family: monospace;
    }

</style>

<body>

    <Navbar

    pagetitle = 'About Us'

    />

    <Bluebox2

    toptitle = 'About'
    topdesc = 'Us'
    middletext = 'The team behind Azimuth'

    />

    <Whiteboxblank>

        <Title
            titletext = "Meet the Members"
        />

        <Leftrow
            leftimage = "blackplaceholder.png"
            leftalttext = "Jeremy"
            lefttitle = "Jeremy"
            leftdesc = "Website Developer"
        />

        <Rightrow
            rightimage = "blackplaceholder.png"
            rightalttext = "Nicholas"
            righttitle = "Nicholas"
            rightdesc = "Backend Developer and Architect" 
        />
        
        <Leftrow
            leftimage = "milescropped.png"
            leftalttext = "Miles"
            lefttitle = "Miles"
            leftdesc = "Assistant Developer and Assistant Architect"
        />

        <Rightrow
            rightimage = "benwithcat.png"
            rightalttext = "Ben"
            righttitle = "Ben"
            rightdesc = "Marketing and Quality Assurance" 
        />

       
    </Whiteboxblank>

    <Footer

    />

</body>