<script>
export default {
    name: 'AppHeader'
}
</script>

<template>
    <header>
        <section class="container">
            <img src="../assets/img/dc-logo.png" alt="dc-logo">
            <div id="navbar">
                <ul>
                    <li class="active"><a href="#"></a>POLLO</li>
                    <li><a href="#"></a>POLLO</li>
                    <li><a href="#"></a>POLLO</li>
                    <li><a href="#"></a>POLLO</li>
                    <li><a href="#"></a>POLLO</li>
                </ul>
            </div>
        </section>
    </header>
</template>

<style scoped>
header {
    background-color: white;
}

section {
    display: flex;
    justify-content: space-between;
    align-items: center;
}

ul {
    display: flex;
    gap: 50px;

    li {
        padding: 50px 0;
    }
}

li.active,
a.active {
    border-bottom: 8px solid #0282F9;
    color: #0282F9;
}
</style>