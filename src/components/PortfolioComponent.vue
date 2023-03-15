<template>
    <div class="container py-5">
        <h1>Portfolio</h1>
        <div class="cards">
            <div class="card" v-for="card in cards" :key="card.title">
                <img :src="card.img" :alt="card.title">
                <div class="content">
                    <div class="top">
                        <h4>{{card.title}}</h4>
                        <p>{{card.paragraph}}</p>
                    </div>
                    <div class="bottom">
                        <i class="fa-solid fa-plus"></i>
                        <i class="fa-solid fa-link"></i>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name: 'PortfolioComponent',
    data: () => ({
        cards: [
            {
                title: '"Che sindaco sei” Il game di ANCI DIGITALE',
                paragraph: 'Portfolio / Smart cities',
                img: 'https://grifomultimedia.it/wp-content/uploads/2022/11/chesindacosei.jpg'
            },
            {
                title: 'Gamification & Recruiting',
                paragraph: 'HR / Portfolio',
                img: 'https://grifomultimedia.it/wp-content/uploads/2022/09/gamification-featured-image.jpg'
            },
            {
                title: 'Marelli Purchasing Academy – Gamification platform',
                paragraph: 'HR / Portfolio',
                img: 'https://grifomultimedia.it/wp-content/uploads/2022/01/marelli-portfolio-1.jpg'
            },
            {
                title: 'Compliance Training per Cassa Depositi e Prestiti',
                paragraph: 'Compliance Training / Portfolio',
                img: 'https://grifomultimedia.it/wp-content/uploads/2022/01/img-5.jpg'
            },
            {
                title: 'Video based learning con attori reali',
                paragraph: 'HR / Portfolio',
                img: 'https://grifomultimedia.it/wp-content/uploads/2021/06/img-bg-portfolio-2.jpg'
            },
            {
                title: 'TCube',
                paragraph: 'Portfolio / Salute e Benessere',
                img: 'https://grifomultimedia.it/wp-content/uploads/2021/04/img-evidenza.jpg'
            }
        ]
    })
}
</script>

<style lang="scss" scoped>
h1 {
    font-size: 3rem;
    color: var(--secondary-color);
    font-weight: 700;
    text-align: center;
}

.cards {
    display: flex;
    flex-flow: row wrap;
    justify-content: center;
    align-items: center;
    gap: 1rem;
    padding: 2rem 0;

    .card {
        position: relative;
        width: calc((100% - 2rem) / 3);
        border: none;
        border-radius: 0;

        .content {
            height: 100%;
            width: 100%;
            opacity: 0;
            transition: .5s ease;
            position: absolute;
            top: 0;
            display: flex;
            flex-flow: column nowrap;
            justify-content: space-between;
            align-items: flex-start;
            padding: 1.5rem;

            .top {

                h4 {
                    color: white;
                    font-weight: 700;
                }

                p {
                    color: #C8C8CA;
                }
            }

            .bottom {
                color: var(--main-color);
                
                i {
                    font-weight: 900;
                    margin-right: 0.5rem;
                }
            }
        }
    }

    .card:hover .content {
        background-color: rgba(0, 0, 0, 0.7);
        opacity: 1;
    }
}
</style>