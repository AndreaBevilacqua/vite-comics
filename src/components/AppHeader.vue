<script>
export default {
    name: 'AppHeader',
    data: () => ({
        links: [
            {
                text: 'Characters',
                url: '#',
                active: false,
            },
            {
                text: 'Comics',
                url: '#',
                active: true,
            },
            {
                text: 'Movies',
                url: '#',
                active: false,
            },
            {
                text: 'TV',
                url: '#',
                active: false,
            },
            {
                text: 'Games',
                url: '#',
                active: false,
            },
            {
                text: 'Collectibles',
                url: '#',
                active: false,
            },
            {
                text: 'Videos',
                url: '#',
                active: false,
            },
            {
                text: 'Fans',
                url: '#',
                active: false,
            },
            {
                text: 'News',
                url: '#',
                active: false,
            },
            {
                text: 'Shop',
                url: '#',
                active: false,
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
                    <li v-for="link in links"><a :href="link.url" :class="{ active: link.active }"></a>{{
                        link.text }}
                    </li>
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