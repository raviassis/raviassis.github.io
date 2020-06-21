<template>
    <header class="header">
        <nav class="navbar navbar-expand">
            <ul class="navbar-nav justify-content-end">
                <li class="nav-item"><nuxt-link class="nav-link" to="/">Home</nuxt-link></li>
                <li class="nav-item"><nuxt-link class="nav-link" to="/sobre">Sobre</nuxt-link></li>
            </ul>
        </nav>
        <div class="header-content">
            <div>
                <h1 class="page-title">Ravi Assis</h1>
                <h2>Software Engineering</h2>
            </div>
        </div>
    </header>
</template>

<style scoped>
@media only screen and (max-width: 500px) {
    .header {
        margin-bottom: 15px;
        height: 40%;
    }
}
@media only screen and (max-width: 900px) {
    .header {
        box-sizing: border-box;
        min-height: 240px;
        padding: 15% 0;
    }
}
.header {
    position: relative;
    width: 100%;
    height: 500px;
    background: #222 no-repeat center center;
    background-size: cover;
    overflow: hidden;
    background-image: url('~assets/images/header3.jpg');
    color: white;
}
.navbar {
    background: linear-gradient(to bottom, rgba(0,0,0,1) 0%,rgba(0,0,0,0) 100%);
}
.navbar .nav-link {
    font-weight: 600;
    color: inherit;
}
.header-content {
    text-align: center;
    text-shadow: 8px 8px 8px black;
    display: flex;
    justify-content: center;
    align-items: center;
}
.page-title {
    margin: 10px 0 10px 0;
    font-size: 4rem;
    letter-spacing: -1px;
    font-weight: 700;
    font-family: "Open Sans", sans-serif;
    animation: fade-in-down 0.6s;
    animation-delay: 0.2s;
}
</style>
