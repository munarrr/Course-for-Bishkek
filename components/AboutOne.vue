<template>
    <section class="about-area about-default-area">
        <div class="container">
            <div class="row">
                <div class="col-lg-5 md-text-center">
                    <div class="layer-style" data-aos="fade-up" data-aos-duration="1000">
                        <div class="thumb tilt-animation">
                            <img src="/images/about/01.jpg" alt="Images">
                        </div>
                        <div class="shape-style1">
                            <img src="/images/shape/circle-line1.png" alt="Images">
                        </div>
                        <ShapeWithAnimation addClassName="shape-style2" imgSrc="/images/shape/circle-shape1.png" data-depth=".6" />
                        <div class="experience-time">
                            <div class="content">32<sup>+</sup> <span>Years of Experience</span></div>
                        </div>
                    </div>
                </div>
                <div class="col-lg-6 offset-lg-1">
                    <div class="about-content">
                        <div class="section-title xs-text-center" data-aos="fade-up" data-aos-duration="1000">
                            <h2 class="title"> ЭФФЕКТИВНЫЕ КУРСЫ  АНГЛИЙСКОГО ЯЗЫКА  В БИШКЕКЕ</h2>
                            <div class="desc">
                                <p class="mt-20">Международная школа ILH(International language house) - одна из ведущих школ английского языка в Кыргызстане.</p>
                            </div>
                        </div>
                        <div class="list-icon-style" data-aos="fade-up" data-aos-duration="1200">
                            <ul>
                                <li><i class="icon icofont-clock-time"></i> Много учеников</li>
                                <li><i class="icon icofont-money-bag"></i> Все преподаватели</li>
                                <li><i class="icon icofont-chart-growth"></i> Сертификат</li>
                                <li><i class="icon icofont-live-support"></i>Носители языка</li>
                                <li><i class="icon icofont-badge"></i> 80% практики/li>
                                <li><i class="icon icofont-unique-idea"></i> Большой опыт</li>
                            </ul>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>
</template>

<script>
    export default {
        components: {
            ShapeWithAnimation: () => import('@/components/ShapeWithAnimation'),
        },
    };
</script>