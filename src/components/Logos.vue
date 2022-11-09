<template>
    <div class="logos-wrapper">
        <h2 class="title-header">Find best logo</h2>
        <div class="item-logos">
            <img class="logo" alt="vueJS logo" src="../assets/logo.svg"> 
    </div>
    <div class="item-logos">
            <img class="logo" alt="github logo" src="../assets/github.svg"> 
    </div>
    <div class="item-logos">
            <img class="logo" alt="steam logo" src="../assets/steam.svg"> 
    </div>
    <div class="item-logos">
            <img class="logo" alt="android logo" src="../assets/android.svg"> 
    </div>
    </div>
</template>

<script>
export default {
    name: 'Logos'
}
</script>

<style scoped>
.title-header {
    margin-bottom: 80px;
    text-align: left;
}
.logos-wrapper {
    width: 62%;
    overflow: hidden;
    margin: auto; 
}

.item-logos {
    float: left;
    margin-right: 50px;
    margin-bottom: 70px;
    width: 150px;
    height: 150px;
}

.item-logos .logo {
    width: 150px;
    height: 150px;
}
</style>