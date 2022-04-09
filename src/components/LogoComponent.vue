<template>
    <div class="wrapper">
        <h2>Find Best Logo</h2>
        <div>
            <div class="content">
                <img src="" alt="" />
            </div>
            <div class="content">
                <img src="" alt="" />
            </div>
        </div>
    </div>
</template>

<script>
    export default {
        name: 'LogoComponent'
    }
</script>

<style scoped>
    .logo {
        width: 70%;
        overflow: hidden;
        margin: auto;
    }


    .content {
        width: 150px;
        height: 150px;
        background-color: cyan;
        float: left;
        margin-left: 2px;
        margin-right: 2px;
        margin-top: 4px;
    }
</style>