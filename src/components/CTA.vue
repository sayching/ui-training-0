<template>
    <div class="cta">
                <div class="content">
                    <h2>Ready to get started?</h2>
                    <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vestibulum consequat scelerisque elit sit amet consequat. Aliquam erat volutpat. Aliquam venenatis gravida nisl sit amet facilisis. Nullam cursus fermentum velit sed laoreet.</p>
                    <a href="https://example.com/" class="btn">Start free trial</a>
                </div>
    </div>
</template>

<script>    
    export default {
        name: "CTA"
    }
</script>

<style scoped>
.content {
    width: 640px; /*can be in percentage also.*/
    height: auto;
    margin: 0 auto;
    padding: 110px;
    position: relative;
}
.cta .btn {
        /* Positioning and sizing */
        display: block;
        width: 200px;
        
        /* Padding and margins */
        padding: 1em;
        margin-top: 10px;
        margin-left: auto;
        margin-right: auto;
        
        /* Text styles */
        color: white; /* CHANGE THIS LINE */
        text-decoration: none;
        font-size: 18px;
        background-color: black;
      
        /* Border styles */
        border: 1px solid black; /* CHANGE THIS LINE */
        border-radius: 10px;
    }
    .cta {
        background-color: #F2F2F2;

    }
    h2 {
        font-weight: bold;
    }
</style>