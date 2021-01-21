<template>
<div class="main_container">
    <div class="container mx-auto cta_home_container">
        <div class="cta_intro_top">
            <h1 class="support_text">SUPPORT CRS</h1>
            <h1 class="cta_intro_header">HOW YOU CAN HELP</h1>
            <div class="intro_divider"></div>
        </div>
    </div>
</div>

</template>

<script>
    export default {
        
    }
</script>

<style scoped>
.intro_divider {
    width: 100px;
    height: 2px;
    background: #71a8d7;
    margin-right: auto;
    margin-left: auto;
    padding-top: 2em;
}
.support_text {
    padding-top: 3em;
    padding-bottom: 1.5em;
}
.cta_home_container {
    height: 500px;
    width: 100%;

}

.main_container {
    background: #3282c6;
    color: white;
}

.cta_intro_top {
    text-align: center;
    font-size: 16px;
    font-family: 'Montserrat', sans-serif;
}

.cta_intro_header {
    font-size: 40px;
    font-family: 'Montserrat', sans-serif;
    font-weight: bold;
}

</style>