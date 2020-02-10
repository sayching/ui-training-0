
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
            <div class="footer-service-extend">
                <ul>
                    <li class="title">PRODUCT</li>
                    <li><a class="link" href="#product1">Product1</a></li>
                    <li><a class="link" href="#product2">Product2</a></li>
                    <li><a class="link" href="#product3">Product3</a></li>
                    <li><a class="link" href="#product4">Product4</a></li>

                </ul>
            </div>
            <div class="footer-service-extend">
                <ul>
                    <li class="title">COMPANY</li>
                    <li><a class="link1" href="#company1">company1</a></li>
                    <li><a class="link1" href="#company2">company2</a></li>
                    <li><a class="link1" href="#company3">company3</a></li>
                    <li><a class="link1" href="#company4">company4</a></li>

                </ul>
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
        width: 25%;
        color: #696969;
    }
    .footer-service-extend ul {
        list-style-type: none;
        padding: 0px;
    }
    .title {
        color: black;
        font-weight: bold;
    }
    .title2 {
        color: black;
        font-size: 24px;
    }
    .t_title {
        color: black;
        font-size: 24px;
        font-weight: bold;
    }
    li {
        margin-bottom: 100px;
    }


    .footer {
        width: 100%;
    }
    .center {
        margin: auto;
        width: 60%;
        padding: 10px;
    }

</style>