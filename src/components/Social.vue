<template>
    <div class="social-proof">
        <div class="social-proof-extend">
            <div class="s-title">
                <p class="trust">Trusted by the World's Best Companies</p>
            </div>
            <div class="logo">
                <img class="image" src="@/assets/logo.png"/>

            </div>
            <div class="logo">
                <img class="image" src="@/assets/logo2.png"/>

            </div><div class="logo">
                <img class="image" src="@/assets/logo3.png"/>

            </div>
            <div class="logo">
                <img class="image" src="@/assets/logo4.png"/>

            </div>
            <div class="logo">
                <img class="image" src="@/assets/logo5.png"/>

            </div>
            <div class="logo">
                <img class="image" src="@/assets/logo6.png"/>

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
        margin-bottom: 10px;
        margin-top: 20px;
        background-color: #F2F2F2;
        height: 300px;
        bottom: 0.75%
    }
    .logo {
        float: left;
        position: relative;
        width: 16%;

    }
    .s-title {

        text-align: center;
        font-weight: bold;
        color: #000000;
    }
   .trust {
        padding: 20px;
        margin-bottom: 30px;
    }

</style>