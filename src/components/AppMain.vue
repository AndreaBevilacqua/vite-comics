<script>
import ComicCard from './comics/ComicCard.vue';

export default {
    name: 'AppMain',
    props: { comics: Array },
    components: { ComicCard },
}
</script>

<template>
    <main>
        <section id="jumbotron">
        </section>
        <div class="top-main">
            <div class="container card-container">
                <ComicCard v-for="(comic, i) in comics" :key="i" :title="comic.series" :image="comic.thumb" />
            </div>
            <button>LOAD MORE</button>
        </div>
        <div class="bottom-main">
            <div class="container">
                <ul>
                    <li class="navbar-main"><img src="../assets/img/buy-comics-digital-comics.png" alt="digital"><a
                            href="#">Digital comics</a></li>
                    <li class="navbar-main"><img src="../assets/img/buy-comics-merchandise.png" alt="merchandise"><a
                            href="#">dc merchandise</a></li>
                    <li class="navbar-main"><img src="../assets/img/buy-comics-subscriptions.png" alt="sub"><a
                            href="#">Subscription</a></li>
                    <li class="navbar-main"><img src="../assets/img/buy-comics-shop-locator.png" alt="lot"><a href="#">Comic
                            shop locator</a></li>
                    <li class="navbar-main"><img src="../assets/img/buy-dc-power-visa.svg" alt="via"><a href="#">Dc power
                            visa</a></li>
                </ul>
            </div>
        </div>
    </main>
</template>

<style lang="scss" scoped>
/* TOP-MAIN */
.top-main {
    background-color: #1C1C1C;
    padding: 3rem;
    color: white;
    font-size: 2rem;
    text-align: center;

    button {
        padding: 0.8rem 3rem;
        background-color: #0282F9;
        outline: none;
        border: none;
        color: white;
        font-weight: bold;
        margin-top: 2rem;
        cursor: pointer;
    }
}

// CARD CONTAINER

.card-container {
    display: flex;
    flex-wrap: wrap;
    margin-top: 2rem;

    .comic-card {
        flex-basis: calc(100% / 6);
    }
}


/* BOTTOM-MAIN */
.bottom-main {
    background-color: #0282F9;
    padding: 3.5rem;
    color: white;
    font-size: 2rem;
}

ul {
    display: flex;
    gap: 3rem;
    color: white;
}

a {
    color: white;
    text-transform: uppercase;
    font-size: 1rem;
}

.navbar-main {
    display: flex;
    align-items: center;
    gap: 20px;
}

#jumbotron {
    height: 400px;
    background-color: red;
    background-image: url(../assets/img/jumbotron.jpg);
}
</style>