<script>
export default {
    name: 'AppFooterBot'
}
</script>

<template>
    <footer>
        <div class="container">
            <div class="sing-in">
                <button>sign-up now!</button>
            </div>
            <div class="socials">
                <h5>follow us</h5>
                <img src="../assets/img/footer-facebook.png" alt="facebook">
                <img src="../assets/img/footer-periscope.png" alt="peri">
                <img src="../assets/img/footer-pinterest.png" alt="pinterest">
                <img src="../assets/img/footer-twitter.png" alt="twitter">
                <img src="../assets/img/footer-youtube.png" alt="youtube">
            </div>
        </div>
    </footer>
</template>

<style scoped>
footer {
    background-color: #303030;
    padding: 2.1rem;
    color: white;
    font-size: 2rem;
}

.container {
    display: flex;
    justify-content: space-between;
    align-items: center;
}

button {
    outline: none;
    padding: 15px;
    border: 2px solid #0282F9;
    background-color: #303030;
    color: white;
    cursor: pointer;
    text-transform: uppercase;
    font-size: 1rem;
    font-weight: bold;
}

.socials {
    display: flex;
    gap: 20px;
    align-items: center;
}

h5 {
    color: #0282F9;
    text-transform: uppercase;
}

img {
    height: 40px;
    width: 40px;
    cursor: pointer;
}
</style>