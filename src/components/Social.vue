<template>
    <div class="social-proof">
        <div class="social-proof-extend">
            <div class="s-title">
                <p class="trust">Trusted by the World's Best Companies</p>
            </div>
            <div class="logo">
                <img src="@/assets/logo.png"/>
                <img src="@/assets/logo2.png"/>
                <img src="@/assets/logo3.png"/>
                <img src="@/assets/logo4.png"/>
                <img src="@/assets/logo5.png"/>
                <img src="@/assets/logo6.png"/>
            </div>
    </div>
</div>
</template>

<script>    
    export default {
        name: "Social"
    }
</script>

<style scoped>
    .social-proof {
        width: 100%;
        height: 260px;
        background: #F2F2F2;
        bottom: 0.75%
    }
    .social-proof-extend .logo {
        width: 680px;
        height: 80px;
        padding: 0px 480px;
    }
    .logo img {
        width: 80px;
        height: 80px;
        padding-right: 30px;
    }
    .s-title {

        text-align: center;
        font-weight: bold;
        color: #000000;
    }
   .trust {
        padding-top: 48px;
        margin-bottom: 30px;
    }

</style>