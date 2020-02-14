<template>
    <div class="toolbar">
        <div class="title">TRADE</div>

        <ul>
            <li><a class="link" href="#link1">Link1</a></li>
            <li><a class="link" href="#link2">Link2</a></li>
            <li><a class="link" href="#link3">Link3</a></li>
            <li><a class="link" href="#link4">Link4</a></li>
            <li><a class="c-signup">Sign up </a></li>
        </ul>


    </div>
</template>

<script>
    export default {
        name: "Toolbar"
    }
</script>

<style scoped>
    .toolbar {
        height: 64px;
        background: white;
    }

    ul {
        list-style-type: none;
        margin: 0;
        padding: 0;
        overflow: hidden;
        background-color: #ffffff;
        float: right;
    }


    li {
        float: left;
        margin: 8px !important;
    }

    li a {
        display: block;
        color: white;
        text-align: center;
        padding: 14px 16px;
        text-decoration: none;

        background: white;
        color: black;
        font-family: Roboto;
        font-size: 18px;
        line-height: 21.09px;
        line-height: 100%;
        
    }

    li a:hover:not(.active) {
        background-color: #ffffff;
    }

    .toolbar .title {
        display: inline-block;
        font-family: Roboto;
        background-color: #ffffff;
        color: black;
        font-size: 24px;
        font-weight: bold;
        float: left;
        padding-left: 24px;
        padding-top: 16px;
    }

    li:last-child {
        padding-right: 40px;
        padding-left: 40px;
        background-color: #ffffff;
        border-bottom-left-radius: 5px;
        border-bottom-right-radius: 5px;
        border-top-left-radius: 5px;
        border-top-right-radius: 5px;
        border-top: 1px solid #000000;
        border-right: 1px solid #000000;
        border-bottom: 1px solid #000000;
        border-left: 1px solid #000000;
        border-color: black;
        color: black;
        font-weight: normal;
        vertical-align: center;

    }
</style>