<template>
    <div class="background_color">
        <div class="container mx-auto main_container">
            <div>
                <h1 class="header_meet">MEET THE CORGIS</h1>
                <div class="divider_div"></div>
            </div>
            <div>
                <p class="para_text">on the live site this area is a carousel view of all the corgis.  It’s broken here because the “Pods – Post Display” plugin must have some outdated code that is not compatible with WordPress 5.5.  </p>
            </div>
        </div>
    </div>
</template>

<script>
    export default {
        
    }
</script>

<style scoped>
    .background_color {
         background: #efeef1;
         padding: 3em;
    }
    .header_meet {
        font-family: 'Montserrat', sans-serif;
        font-size: 40px;
        font-weight: bold;

    }
    .main_container {
        height: 350px;
        display: flex;
        flex-direction: column;
        align-items: center;
        justify-content: center;
    }
    .divider_div {
        width: 100px;
        height: 2px;
        background: black;
        margin-left: auto;
        margin-right: auto;
        margin-top: 2em;
        margin-bottom: 2em;
    }
    .para_text {
        text-align: center;
        padding-right: 3em;
        padding-left: 3em;
    }
    @media screen and (min-width:700px){
        .para_text {
            font-size: 20px;
        }
        
    }
    @media only screen and (max-width: 600px) {
        .header_meet {
            text-align: center;
            padding-top: 1.5em;
        }  
        .para_text {
            padding-left: 2.5em;
            padding-right: 2.5em;
            margin-bottom: 2em;
        } 
        .background_color {
            padding: 0;
            min-height: 475px;
        }
    }
</style>