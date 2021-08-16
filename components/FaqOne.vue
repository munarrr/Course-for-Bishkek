<template>
    <section class="faq-area faq-default-area" :style="{ backgroundImage: `url('/images/photos/bg-faq.jpg')` }">
        <div class="container">
            <div class="row">
                <div class="col-lg-8">
                    <div class="faq-content" data-aos="fade-up" data-aos-duration="1100">
                        <div class="section-title xs-text-center">
                            <h2 class="title text-white">АВТОРСКАЯ РАЗРАБОТКА  СОВРЕМЕННЫХ  <span class="bottom-color-style2">МЕТОДОВ ТОЛЬКО ЭФФЕКТИВНОЕ ОБУЧЕНИЕ!.</span></h2>
                        </div>
                        <div class="accordion-content">
                            <AccordionStyleOne />
                        </div>
                        <div class="text-center">
                            <a href="#" class="btn btn-theme btn-white btn-border">Еще есть вопросы <i class="icon icofont-long-arrow-right"></i></a>
                        </div>
                    </div>
                </div>
            </div>
        </div>
        <div class="layer-shape">
            <div class="layer-shape-one"  data-aos="fade-up" data-aos-duration="1000">
                <img class="img-shape1 tilt-animation" src="/images/photos/faq1.png" alt="Virtuf-Image">
                <img class="img-shape2" src="/images/shape/1.png" alt="Virtuf-Image">
                <img class="img-shape3" src="/images/shape/2.png" alt="Virtuf-Image">
            </div>
            <div class="layer-shape-two">
                <img src="/images/shape/circle-line2.png" alt="Virtuf-Image">
            </div>
            <div class="layer-shape-three">
                <img src="/images/shape/circle-line3.png" alt="Virtuf-Image">
            </div>
        </div>
    </section>
</template>

<script>
    export default {
        components: {
            AccordionStyleOne: () => import('@/components/AccordionStyleOne'),
        },
    };
</script>