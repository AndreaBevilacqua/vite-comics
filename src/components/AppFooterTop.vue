<script>
export default {
    name: 'AppFooterTop'
}
</script>

<template>
    <footer>
        <div class="container">
            <div class="links-footer">
                <div class="links-col">
                    <h3>dc comics</h3>
                    <ul>
                        <li><a href="#">Characters</a></li>
                        <li><a href="#">Comics</a></li>
                        <li><a href="#">Movies</a></li>
                        <li><a href="#">TV</a></li>
                        <li><a href="#">Games</a></li>
                        <li><a href="#">Videos</a></li>
                        <li><a href="#">News</a></li>
                    </ul>
                    <h3>Shop</h3>
                    <ul>
                        <li><a href="#">Shop DC</a></li>
                        <li><a href="#">Shop DC Collectibles</a></li>
                    </ul>
                </div>
                <div class="links-col">
                    <h3>dc comics</h3>
                    <ul>
                        <li><a href="#">Terms Of Use</a></li>
                        <li><a href="#">Privacy</a></li>
                        <li><a href="#">Ad Choices</a></li>
                        <li><a href="#">Advertising</a></li>
                        <li><a href="#">Jobs</a></li>
                        <li><a href="#">Subscriptions</a></li>
                        <li><a href="#">Talents</a></li>
                        <li><a href="#">CPSC</a></li>
                        <li><a href="#">Ratings</a></li>
                        <li><a href="#">Shop Help</a></li>
                    </ul>
                </div>
                <div class="links-col">
                    <h3>sites</h3>
                    <ul>
                        <li><a href="#">DC</a></li>
                        <li><a href="#">MAD Magazine</a></li>
                        <li><a href="#">DC Kids</a></li>
                        <li><a href="#">DC Universe</a></li>
                        <li><a href="#">DC Power Visa</a></li>
                    </ul>
                </div>
            </div>
            <div class="img-footer">
                <!-- <img src="../assets/img/dc-logo-bg.png" alt=""> -->
            </div>
        </div>
    </footer>
</template>

<style scoped>
footer {
    background-image: url(../assets/img/footer-bg.jpg);
    background-repeat: no-repeat;
    background-size: cover;
    height: 380px;
    padding: 2rem;
}

.container {
    display: flex;
    justify-content: space-between;
}

h3 {
    text-transform: uppercase;
    color: white;
    margin: 10px 0;
}

a {
    color: gray;
    font-size: 0.8rem;
}

.links-footer {
    display: flex;
    gap: 20px;
}
</style>