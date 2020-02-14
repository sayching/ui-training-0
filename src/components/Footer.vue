
<template>
    <div class="footer">
        <div class="footer-service">
            <div class="footer-service-extend">
                <ul>
                    <li class="t_title">TRADE</li>

                </ul>
            </div>
            <div class="footer-service-extend" style="
        padding-bottom: 37px;">
                <ul>
                    <li class="title">Latest Blog Post</li>
                    <li class="title2">Ready to get started?</li>
                    <div class="center"><p> Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vestibulum consequat scelerisque elit sit amet consequat. Aliquam erat volutpat. Aliquam venenatis gravida nisl sit amet facilisis. Nullam cursus fermentum velit sed laoreet.</p></div>
                </ul>
            </div>
            <div class = "vertical"></div> 
            <div class="footer-service-extend1">
                <ul>
                    <li><a class="title" href="#PRODUCT">PRODUCT</a></li>
                    <li><a class="link" href="#product1">Product1</a></li>
                    <li><a class="link" href="#product2">Product2</a></li>
                    <li><a class="link" href="#product3">Product3</a></li>
                    <li><a class="link" href="#product4">Product4</a></li>

                </ul>
                <div class="link2">
                    <p>&copy; 2010 - 2020</p>
                </div>
            </div>

            <div class="footer-service-extend1">
                <ul>
                    <li><a class="title" href="COMPANY">COMPANY</a></li>
                    <li><a class="link1" href="#company1">company1</a></li>
                    <li><a class="link1" href="#company2">company2</a></li>
                    <li><a class="link1" href="#company3">company3</a></li>
                    <li><a class="link1" href="#company4">company4</a></li>

                </ul>
                <div class="link2">
                    <p><a class="privacy" href="privacy">Privacy Terms</a></p>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
    export default {
        name: "Footer"
    }
</script>

<style>
    .footer-service {
        font-size: 14px;
        line-height: 17px;
        padding: 50px 6.66%;
        display: flow-root;
    }

    .footer-service-extend {
        float: left;
        width: 24%;
        color: #696969;
        margin: 0px;
    }
    .footer-service-extend ul {
        list-style-type: none;
        padding: 0px;
    }
    .title {
        color: black;
        font-weight: bold;
        text-align: justify;
    }
    .title2 {
        color: black;
        font-size: 24px;
        text-align: justify;
    }
    .t_title {
        color: black;
        font-size: 24px;
        font-weight: bold;
        text-align: justify;
    }
    li {
        margin-bottom: 10px;
        
    }

    .footer {
        width: 100%;
    }
    .center {
        margin: auto;
        width: auto;
        /* padding: 10px; */
        margin: 0px 0px 10px;
        text-align: justify;
    }
    .footer-service-extend1 {
        float: left;
        width: 15%;
        color: #696969;
    }
    .footer-service-extend1 ul {
        list-style-type: none;
        padding: 0px;
    }
    .vertical { 
            border-left: 2px solid black; 
            height: 300px; 
            position:absolute; 
            left: 50%; 
        }
    p {
        margin-bottom: 80px;

    }
    a.privacy{
        margin-bottom: 80px;
    }

</style>