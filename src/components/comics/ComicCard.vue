<script>
export default {
    name: 'Comic Card',
    props: {
        image: String,
        title: String
    }
}
</script>

<template>
    <div class="comic-card">
        <img :src="image" :alt="title">
        <h6>{{ title }}</h6>
    </div>
</template>

<style lang="scss" scoped>
.comic-card {
    padding: 20px;

    img {
        height: 200px;
        width: 300px;
    }

    h6 {
        font-size: 0.8rem;
        text-transform: uppercase;
        text-align: left;
        margin-top: 10px;
    }
}
</style>