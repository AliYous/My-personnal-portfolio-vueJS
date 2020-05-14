<template>
    <div class="main-row">
        <h2 class="hello-text"> Bonjour, ici Ali. </h2>
        <div class="paragraph-container container">
            <p>
                Since beginning my journey as a freelance designer nearly 8 years ago, I've done remote work for agencies,
                consulted for startups, and collaborated with talented people to create digital products for both business and consumer use.
                I'm quietly confident, naturally curious, and perpetually working on improving my chops one design problem at a time.
            </p>
        </div>
        
    </div>
</template>

<script>
export default {
    name: 'AboutMe'

}
</script>

<style>
    .main-row {
        height: 40vh;
        display: flex;
        flex-direction: column;
        align-items: center;
        justify-content: center;
        color: white;
        background-color: rebeccapurple;
    }
    .paragraph-container {
        width: 50%;
        text-align: center;
    }
</style>