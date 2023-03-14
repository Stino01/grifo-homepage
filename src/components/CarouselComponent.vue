<template>
    <vueper-slides
        class="no-shadow"
        :arrows= false
        :bullets= false
        :autoplay= true
        :duration= 2000
        :visible-slides="4"
        :slide-ratio="1 / 4"
        :dragging-distance="70">
        <vueper-slide v-for="i in slides" :key="i" :image="i.img"/>
    </vueper-slides>
</template>

<script>
import { VueperSlides, VueperSlide } from 'vueperslides'
import 'vueperslides/dist/vueperslides.css'

export default {
    name: 'CarouselVue',
    components: { VueperSlides, VueperSlide },
    data: () => ({
        slides: [
            {
                title: 'Menti pratiche',
                img: 'https://www.grifomultimedia.it/wp-content/uploads/2020/12/logo-menti-pratiche.png'
            },
            {
                title: 'Carrefour',
                img: 'https://www.grifomultimedia.it/wp-content/uploads/2020/08/logo-carrefour.jpg'
            },
            {
                title: 'Tim',
                img: 'https://www.grifomultimedia.it/wp-content/uploads/2019/10/tim-logo.jpg'
            }, 
            {
                title: 'Nespresso',
                img: 'https://www.grifomultimedia.it/wp-content/uploads/2019/10/nespresso.jpg'
            },
            {
                title: 'GTT',
                img: 'https://www.grifomultimedia.it/wp-content/uploads/2019/10/GTT-LOGO.jpg'
            },
            {
                title: 'Gnk',
                img: 'https://www.grifomultimedia.it/wp-content/uploads/2019/10/gkn.jpg'
            },
            {
                title: 'Enel',
                img: 'https://www.grifomultimedia.it/wp-content/uploads/2019/10/enel.jpg'
            }, 
            {
                title: 'BPM',
                img: 'https://www.grifomultimedia.it/wp-content/uploads/2019/10/BPM-LOGO.jpg'
            },
            {
                title: 'Agos',
                img: 'https://www.grifomultimedia.it/wp-content/uploads/2019/10/agos.jpg'
            },
            {
                title: 'Lutech',
                img: 'https://www.grifomultimedia.it/wp-content/uploads/2022/11/lutech.jpg'
            },
            {
                title: 'MPS',
                img: 'https://www.grifomultimedia.it/wp-content/uploads/2022/04/logo-mps.png'
            }, 
            {
                title: 'CDC',
                img: 'https://www.grifomultimedia.it/wp-content/uploads/2020/08/gruppo-cassa-depositi-e-crediti.jpg'
            },
            {
                title: 'Credit Agricole',
                img: 'https://www.grifomultimedia.it/wp-content/uploads/2020/05/logo-credit-agricole.png'
            },
            {
                title: 'Ubs',
                img: 'https://www.grifomultimedia.it/wp-content/uploads/2019/10/ubs2.png'
            },
            {
                title: 'Prink',
                img: 'https://www.grifomultimedia.it/wp-content/uploads/2019/10/prink.jpg'
            }, 
            {
                title: 'Poste',
                img: 'https://www.grifomultimedia.it/wp-content/uploads/2019/10/postenew.png'
            },
        ]
    })
}
</script>

<style lang="scss" scoped>

</style>