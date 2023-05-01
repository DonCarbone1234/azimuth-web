<script lang = "ts">
    import Navbar from "../../components/navbar.svelte";
    import Footer from "../../components/footer.svelte";
    import Orangeblank from "../../components/orangeblank.svelte";
    import Orangetitle from "../../components/orangetitle.svelte";
    import Browser from "../../components/browser.svelte";
    import Browserbox from "../../components/browserbox.svelte";
</script>



<style>

    body {
        font-family: monospace;
        margin: 0;
    }

</style>



<body>

    <Navbar
        pagetitle = "Browsers"
    />

    <Orangeblank>

        <Orangetitle
            titletext = "Browser Launch"
        />

        <Browserbox>
        
            <Browser
                linkto = "/chrome"
                browserlogo = "chromelogo.png"
                alttext = "Chrome"
                browsername = "Chrome"
            />

            <Browser
                linkto = "/edge"
                browserlogo = "Microsoft_Edge_logo_(2019).png"
                alttext = "Edge"
                browsername = "Edge"
            />

            <Browser
                linkto = "/firefox"
                browserlogo = "Firefox_logo,_2017.png"
                alttext = "Firefox"
                browsername = "Firefox"
            />

            <Browser
                linkto = "/brave"
                browserlogo = "Brave_icon_lionface.png"
                alttext = "Brave"
                browsername = "Brave"
            />

            <Browser
                linkto = "/tor"
                browserlogo = "tortransparent1.png"
                alttext = "Tor"
                browsername = "Tor"
            />

            <Browser
                linkto = "/retroarch"
                browserlogo = "Retroarch2png.png"
                alttext = "RetroArch"
                browsername = "RetroArch"
            />

        </Browserbox>

    </Orangeblank>

    <Footer 

    />

</body>

