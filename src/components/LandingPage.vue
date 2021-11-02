<template>
    <div class="landing">
        <div class="container bg-gradient">
            <div class="hero-banner">
                <h2> JOIN THE STRUGGLE. </h2>
                <p>
                    The month long struggle takes place <span> Nov 1st - Nov 30th </span>, join the struggle by contacting a member of the council.
                </p>
                <h2> The Council </h2>
                <ul>
                    <li> Parker: <a href="mailto:parkerfreestone@gmail.com">parkerfreestone@gmail.com </a> </li>
                    <li> Nick: <a href="mailto:motermaniac13@gmail.com">motermaniac13@gmail.com </a> </li>
                    <li> Bridge: <a href="mailto:bobs1alis1@gmail.com">bobs1alis1@gmail.com </a> </li>
                    <li> Ben: <a href="mailto:hamundben@gmail.com">hamundben@gmail.com </a> </li>
                    <li> Carter: <a href="mailto:cklarson319@gmail.com">cklarson319@gmail.com </a> </li>
                </ul>
            </div>
            <div class="fuckingben">
                <img src="@/assets/logo.png" alt="">
            </div>
        </div>
        <div class="wavecheck">
            <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1440 320">
                <path fill="#111827" fill-opacity="1" d="M0,160L30,149.3C60,139,120,117,180,101.3C240,85,300,75,360,74.7C420,75,480,85,540,112C600,139,660,181,720,165.3C780,149,840,75,900,48C960,21,1020,43,1080,64C1140,85,1200,107,1260,106.7C1320,107,1380,85,1410,74.7L1440,64L1440,320L1410,320C1380,320,1320,320,1260,320C1200,320,1140,320,1080,320C1020,320,960,320,900,320C840,320,780,320,720,320C660,320,600,320,540,320C480,320,420,320,360,320C300,320,240,320,180,320C120,320,60,320,30,320L0,320Z"></path>
            </svg>
        </div>
        <div class="rules bg-purple">
            <div class="">
                General Rules For The Cause:
            </div>
            <div class="list">
                <div class="item">
                    A $5 entry fee is required to join
                </div>
                <div class="item">
                    This is a full transparency cause, if you lie, you must put in an additional $5 or be disqualified.
                </div>
            </div>
        </div>
    </div>
</template>

<script>

export default ({
    name: "LandingPage",
    
})
</script>

<style scoped>
    .rules {
        height: 100vh;
    }
    .hero-banner {
        height: 40vh;
    }

    ul {
        list-style-type: none;
    }
</style>
