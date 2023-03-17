<template>
    <section id="service">
        <div class="card img1 col-xs-12 col-md-4">
            <div class="data">
                <h1>Digital Learning</h1>
                <a href="#">Scopri</a>
            </div>
        </div>
        <div class="card img2 col-xs-12 col-md-4">
            <div class="data">
                <h1>Gamification</h1>
                <a href="#">Scopri</a>
            </div>
        </div>
        <div class="card img3 col-xs-12 col-md-4">
            <div class="data">
                <h1>Servizi & Consulenza</h1>
                <a href="#">Scopri</a>  
            </div>
        </div>
    </section>
</template>

<script>
export default {
    name: "ServiceComponent",
    components: {

    }
}
</script>

<style lang="scss" scoped>
#service {
    display: flex;
    flex-flow: row wrap;

    .card {
        background-size: cover;
        padding: 18rem 0;
        border-radius: 0;
        border: none;
        position: relative;

        .data {
            position: absolute;
            top: 50%;
            left: 50%;
            transform: translate(-50%, -50%);
            color: white;
            text-align: center;
            
            h1 {
                font-size: 3rem;
                font-weight: 700;
            }

            a {
                font-size: 1.5rem;
                color: white;
                padding: 0.7rem 2rem;
                border: 5px solid white;
                text-transform: uppercase;
                text-decoration: none;
            }
        }
    }

    .img1 {
        background-image: url('https://grifomultimedia.it/wp-content/uploads/2019/11/Grifo-Multimedia-Home-Digital-Learning-1.jpg');
    }

    .img2 {
        background-image: url('https://grifomultimedia.it/wp-content/uploads/2020/01/Grifo-Multimedia-Home-Gamification-2.jpg');
    }
    
    .img3 {
        background-image: url('https://grifomultimedia.it/wp-content/uploads/2019/11/Grifo-Multimedia-Home-Servizi-e-Consulenza-01.jpg');
    }
}
</style>