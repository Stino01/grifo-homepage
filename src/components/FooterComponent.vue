<template>
    <footer>
        <div class="container row">
            <div class="left col-xs-12 col-md-4">
                <img src="https://www.grifomultimedia.it/wp-content/uploads/2020/03/grifo-logo-white-2.png" alt="">
                <img src="https://www.grifomultimedia.it/wp-content/uploads/2019/12/Logo-Soges-Holding-Company.png" alt="">
                <div class="icons">
                    <i class="fa-brands fa-facebook-f"></i>
                    <i class="fa-brands fa-twitter"></i>
                    <i class="fa-brands fa-linkedin-in"></i>
                    <i class="fa-brands fa-instagram"></i>
                </div>
                <h4>Iscriviti alla newsletter e resta sempre aggiornato.</h4>
                <input type="text" placeholder="Email *">
                <a href="">Iscriviti</a>
            </div>
            <div class="center col-xs-12 col-md-4">
                <h4>Grifo multimedia Srl ©</h4>
                <p>BARI *, Via Bruno Zaccaro, 17/19 – 70126<br><span>Tel. +39 080.4602093 - Fax +39 080.5481762</span> <br>"Orario di ricevimento segreteria didattica: Lun - Ven 9:00 - 13:00"</p>
                <p>MILANO, Piazzale Aquileia, 10 – 20144<br><span>Tel. +39 02.48009872 - Fax +39 02.48021740</span></p>
                <p>FIRENZE, Via Masaccio, 62 – 50132 <br><span>Tel. +39 055.0620680</span></p>
                <p>TORINO, Corso Ferrucci, 24 – 10138<br><span>Tel. +39 011.5638611 - Fax +39 011.5638610</span></p>
                <p>PADOVA, Via San Crispino, 106 - 35129</p>
                <p>CEPRANO (FR) *, Via Valle dei Liri SNC - 03024</p>
                <p>(*) sedi accreditate presso le rispettive regioni per attività di formazione professionale</p>
            </div>
            <div class="right col-xs-12 col-md-4">
                <img src="https://www.grifomultimedia.it/wp-content/uploads/2020/12/grifo-mappa-italia.png" alt="">
            </div>
        </div>
    </footer>
</template>

<script>
export default {
    
}
</script>

<style lang="scss" scoped>
footer {
    background-color: #16171D; 
    color: white;

    .row {
        margin: 0 auto;
        padding: 5rem 0;
    }

    .left {
        
        img {
            padding: 0 0 1rem 0;
        }

        .icons {
            font-size: 1.5rem;
            padding: 1rem 0;
            
            i {
                margin-right: 0.5rem;
            }
        }

        h4 {
            font-size: 1.2rem;
            padding: 1rem 0 0 0;
        }

        input {
            width: 70%;
            padding: 0.5rem 1rem;
            border-color: rgba(225,225,225,1);
            border-width: 1px;
            border-style: solid;
            margin-bottom: 0.5rem;
        }

        a {
            font-size: 0.8rem;
            background-color: var(--secondary-color);
            padding: 0.5rem 2rem;
            color: var(--main-color);
            text-decoration: none;
        }
    }

    .center {
        p {
            font-size: 0.9rem;
            color: #4B4C4F;

            span {
                color: #5D5D5D;
            }
        }
    }
}

img {
    width: 100%;
}
</style>