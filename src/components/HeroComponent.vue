<template>
    <section id="hero">
        <div id="carouselExampleIndicators" class="carousel slide">
            <div class="carousel-indicators">
                <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="0" class="active" aria-current="true" aria-label="Slide 1"></button>
                <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="1" aria-label="Slide 2"></button>
                <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="2" aria-label="Slide 3"></button>
                <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="3" aria-label="Slide 4"></button>
                <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="4" aria-label="Slide 5"></button>
                <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="5" aria-label="Slide 6"></button>
                <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="6" aria-label="Slide 7"></button>
                <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="7" aria-label="Slide 8"></button>
            </div>
            <div class="carousel-inner">
                <div class="carousel-item active">
                    <img src="https://www.grifomultimedia.it/wp-content/uploads/2022/11/lutechcase-1.jpg" class="d-block w-100" alt="...">
                </div>
                <div class="carousel-item">
                    <img src="https://www.grifomultimedia.it/wp-content/uploads/2019/10/slide-g4s-award.jpg" class="d-block w-100" alt="...">
                </div>
                <div class="carousel-item">
                    <img src="https://www.grifomultimedia.it/wp-content/uploads/2019/10/bg3.jpg" class="d-block w-100" alt="...">
                </div>
                <div class="carousel-item">
                    <img src="https://www.grifomultimedia.it/wp-content/uploads/2022/04/slide-1-digital-mindset.jpg" class="d-block w-100" alt="...">
                </div>
                <div class="carousel-item">
                    <img src="https://www.grifomultimedia.it/wp-content/uploads/2022/04/slide-2-sicurezza-informazioni.jpg" class="d-block w-100" alt="...">
                </div>
                <div class="carousel-item">
                    <img src="https://www.grifomultimedia.it/wp-content/uploads/2022/04/slide-3-marelli-gamification.jpg" class="d-block w-100" alt="...">
                </div>
                <div class="carousel-item">
                    <img src="https://www.grifomultimedia.it/wp-content/uploads/2022/04/slide-5-nabbovaldo.jpg" class="d-block w-100" alt="...">
                </div>
                <div class="carousel-item">
                    <img src="https://www.grifomultimedia.it/wp-content/uploads/2022/04/slide-6-eventi-interattivi1.jpg" class="d-block w-100" alt="...">
                </div>
            </div>
            <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide="prev">
                <span class="carousel-control-prev-icon" aria-hidden="true"></span>
                <span class="visually-hidden">Previous</span>
            </button>
            <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide="next">
                <span class="carousel-control-next-icon" aria-hidden="true"></span>
                <span class="visually-hidden">Next</span>
            </button>
        </div>
    </section>
</template>

<script>
export default {
    name: 'HeroComponent'
}
</script>

<style lang="scss" scoped>
#hero {
    height: 100vh;

    .carousel{
        height: 100%;

        .carousel-inner {
            height: 100%;

            .carousel-item {
                height: 100%;
            
                img {
                    height: 100%;
                }
            }
        }
    }
}
</style>