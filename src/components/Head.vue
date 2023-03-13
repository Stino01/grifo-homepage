<template>
    <header>
        <nav class="navbar navbar-expand-lg fixed-top">
            <div class="container-fluid">
                <img src="https://www.grifomultimedia.it/wp-content/uploads/2020/03/grifo-logo-1.png" alt="">
                <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation"><span class="navbar-toggler-icon"></span></button>
                <div class="collapse navbar-collapse" id="navbarNav">
                    <ul class="navbar-nav">
                        <li class="nav-item"><a class="nav-link" href="#">Home</a></li>
                        <li class="nav-item"></li>
                        <li class="nav-item dropdown">
                            <a class="nav-link dropdown-toggle" role="button" data-bs-toggle="dropdown" aria-expanded="false" href="#">Soluzioni</a>
                            <ul class="dropdown-menu">
                                <li><a class="dropdown-item" href="#">Digital learning</a></li>
                                <li><a class="dropdown-item" href="#">Gamification</a></li>
                                <li><a class="dropdown-item" href="#">Servizi & Consulenza</a></li>
                            </ul>
                        </li>
                        <li class="nav-item dropdown">
                            <a class="nav-link dropdown-toggle" role="button" data-bs-toggle="dropdown" aria-expanded="false" href="#">Azienda</a>
                            <ul class="dropdown-menu">
                                <li><a class="dropdown-item" href="#">Chi siamo</a></li>
                                <li><a class="dropdown-item" href="#">Cosa facciamo</a></li>
                                <li><a class="dropdown-item" href="#">Perchè scegliere Grifo</a></li>
                                <li><a class="dropdown-item" href="#">L'innovazione è un gioco serio</a></li>
                            </ul>
                        </li>
                        <li class="nav-item dropdown">
                            <a class="nav-link dropdown-toggle" role="button" data-bs-toggle="dropdown" aria-expanded="false" href="#">Risorse</a>
                            <ul class="dropdown-menu">
                                <li><a class="dropdown-item" href="#">Portfolio</a></li>
                                <li><a class="dropdown-item" href="#">Case Study</a></li>
                                <li><a class="dropdown-item" href="#">Progetti R&S</a></li>
                                <li><a class="dropdown-item" href="#">Whitepaper</a></li>
                            </ul>
                        </li>
                        <li class="nav-item"><a class="nav-link" href="#">Blog</a></li>
                        <li class="nav-item"><a class="nav-link" href="#">Contatti</a></li>
                    </ul>
                </div>
            </div>
        </nav>
    </header>
</template>

<script>
export default {
    name: "HeaderFixed",
}
</script>

<style lang="scss" scoped>
.navbar {
    background-color: white;
    padding: 2rem;

    img {
        width: 12rem;
    }
    
    .navbar-collapse {
        justify-content: flex-end;

        .nav-link {
            padding: 0 0 0 2rem;
            color: black;
            font-weight: 500;
        }
    }
}
</style>