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
    width: 640px; 
    height: auto;
    margin: 0 auto;
    padding: 110px;
    position: relative;
}
.cta .btn {

        display: block;
        width: 200px;
        

        padding: 1em;
        margin-top: 10px;
        margin-left: auto;
        margin-right: auto;

        color: white; 
        text-decoration: none;
        font-size: 18px;
        background-color: black;
      
        border: 1px solid black;
        border-radius: 10px;
    }
    .cta {
        background-color: #F2F2F2;

    }
    h2 {
        font-weight: bold;
    }
</style>