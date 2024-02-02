<script>
export default {
    name: 'AppMain'
}
</script>

<template>
    <main>
        <section id="jumbotron">
        </section>
        <div class="top-main">
            <div class="container">
                <p>Contenuto</p>
            </div>
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

<style scoped>
.top-main {
    background-color: #1C1C1C;
    padding: 3rem;
    color: white;
    font-size: 2rem;
}

.bottom-main {
    background-color: #0282F9;
    padding: 3.5rem;
    color: white;
    font-size: 2rem;
}

img {
    height: 3rem;
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