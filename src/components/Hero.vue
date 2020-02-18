<template>
    <div class="hero">
            <div class="hero-extend">
                <div class="content">
                    <h2>Your Best Value<br>
                    Proposition</h2>
                    <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
                    <p>Vestibulum consequat scelerisque elit sit amet consequat.</p>
                    <p>Aliquam erat volutpat. Aliquam venenatis gravida nisl sit</p>
                    <p>amet facilisis. Nullam cursus fermentum velit sed laoreet.</p>
                    <a href="https://example.com/" class="btn">Start free trial</a>
                </div>
            </div>
            <div class="hero-extend">
                <div class="indicator">
                <span class="dot" onclick="currentSlide(1)"></span> 
                <span class="dot" onclick="currentSlide(2)"></span> 
                <span class="dot" onclick="currentSlide(3)"></span> 
                </div>
            </div>
    </div>
</template>

<script>    
    export default {
        name: "Hero"
    }
</script>

<style scoped>

    
    .hero-extend {
        float: left;
        width: 50%;

    }
    .hero::after {
        content: "";
        display: table;
        clear: both;
    }
    .hero .content {
        margin-top: 60px;
        margin-bottom: 30px;
    }
    .hero .indicator {
        text-align:left;
        border-style: solid;
        border-width: 1px;
        border-color: black;
        border-radius: 3px;
        width: auto;
        height: 580px;
        margin-right: 100px;
        margin-top: 60px;
        margin-bottom: 30px;
    }
    .hero .btn {
        /* Positioning and sizing */
        display: block;
        width: 200px;
        
        /* Padding and margins */
        padding: 1em;
        margin-top: 50px;
        margin-left: auto;
        margin-right: auto;
        
        /* Text styles */
        color: white; /* CHANGE THIS LINE */
        text-decoration: none;
        font-size: 1.5em;
        background-color: black;
        
        /* Border styles */
        border: 1px solid black; /* CHANGE THIS LINE */
        border-radius: 10px;
    }
    p {
        display: block;
        margin-top: 1em;
        margin-bottom: 1em;
        margin-left: 0;
        margin-right: 0;
        font-size: 20px;
        align-content: left;
    }
    h2 {
        font-size: 56px;
        align-self: left;
        margin-top: 100px;
    }
    .dot {
        cursor: pointer;
        height: 12px;
        width: 12px;
        margin: 0 2px;
        background-color: #bbb;
        border-radius: 50%;
        display: inline-block;
        transition: background-color 0.6s ease;
    }

    .active, .dot:hover {
        background-color: #717171;
    }
</style>