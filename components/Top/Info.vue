<script setup>

</script>

<template>
    <div class="info">
        <span>Tel: 700 000 000</span>
        <span>email: kontakt@pornhub.com</span>
    </div>
</template>

<style scoped lang="scss">
.info {
    display: flex;
    flex-wrap: wrap;
    width: 100%;
    height: 50px;
    background-color: black;
    color: white;
    justify-content: center;
    align-items: center;
    font-size: 20px;

    @media (max-width: 465px) {
        height: 100px;
    }

    span {
        margin: 0 10px 0 10px;
    }
}
</style>