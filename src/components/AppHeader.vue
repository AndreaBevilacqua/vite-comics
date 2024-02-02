<script>
export default {
    name: 'AppHeader',
    data: () => ({
        links: [
            {
                text: 'Characters',
                url: '#',
                current: false,
            },
            {
                text: 'Comics',
                url: '#',
                current: true,
            },
            {
                text: 'Movies',
                url: '#',
                current: false,
            },
            {
                text: 'TV',
                url: '#',
                current: false,
            },
            {
                text: 'Games',
                url: '#',
                current: false,
            },
            {
                text: 'Collectibles',
                url: '#',
                current: false,
            },
            {
                text: 'Videos',
                url: '#',
                current: false,
            },
            {
                text: 'Fans',
                url: '#',
                current: false,
            },
            {
                text: 'News',
                url: '#',
                current: false,
            },
            {
                text: 'Shop',
                url: '#',
                current: false,
            },
        ]
    }),
}
</script>

<template>
    <header>
        <section class="container">
            <img src="../assets/img/dc-logo.png" alt="dc-logo">
            <div id="navbar">
                <ul>
                    <li v-for="link in links"><a href="#"></a>{{ link.text }}</li>
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