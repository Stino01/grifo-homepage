<template>
    <section>
        <div class="container py-5">
            <h1>Azienda</h1>
            <p>Grifo è una Pmi innovativa che da oltre venti anni sviluppa soluzioni di e-learning & gamification per l’empowerment delle persone e delle organizzazioni.</p>
            <a href="#">Scopri</a>
        </div>
        <div class="training py-5">
            <div class="container">
                <div class="block">
                    <img src="https://grifomultimedia.it/wp-content/uploads/2020/01/Grifo-Multimedia-icone-counter-01.png" alt="Multimedia1">
                    <h1>24</h1>
                    <p>Anni nel digital learning & gamification</p>
                </div>
                <div class="block">
                    <img src="https://grifomultimedia.it/wp-content/uploads/2020/01/Grifo-Multimedia-icone-counter-02.png" alt="Multimedia2">
                    <h1>900.000</h1>
                    <p>Ore di formazione erogate</p>
                </div>
                <div class="block">
                    <img src="https://grifomultimedia.it/wp-content/uploads/2020/01/Grifo-Multimedia-icone-counter-03.png" alt="Multimedia3">
                    <h1>450.000</h1>
                    <p>Persone formate</p>
                </div>
            </div>
        </div>
    </section>
</template>

<script>
export default {
    name: 'FactoryComp'
}
</script>

<style lang="scss" scoped>
.container {
    display: flex;
    flex-flow: column nowrap;
    justify-content: center;
    align-items: center;

    h1 {
        font-size: 3rem;
        color: var(--secondary-color);
        font-weight: 700;
    }

    p {
        font-size: 2rem;
        font-weight: 500;
        text-align: center;
        width: 50%;
        padding: 3rem 0;
    }

    a {
        font-size: 1.3rem;
        background-color: var(--secondary-color);
        padding: 0.5rem 2rem;
        color: var(--main-color);
        text-transform: uppercase;
        text-decoration: none;
        font-weight: 700;
    }
}

.training {
    background-color: black;

    .container {
        display: flex;
        flex-flow: row wrap;
        justify-content: center;
        align-items: center;

        .block {
            width: calc(100% / 3);
            display: flex;
            flex-flow: column nowrap;
            justify-content: stretch;
            align-items: center;

            h1 {
                color: var(--main-color);
            }

            p {
                width: 100%;
                color: var(--main-color);
                font-size: 1.5rem;
                padding: 0;
            }
        }
    }
}
</style>