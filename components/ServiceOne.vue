<template>
    <section class="service-area service-default-area">
        <div class="container">
            <div class="row">
                <div class="col-lg-8 col-xl-6 m-auto">
                    <div class="section-title text-center" data-aos="fade-up" data-aos-duration="1000">
                        <h2 class="title">6 ПРИЧИН УЧИТЬСЯ АНГЛИЙСКОМУ ЯЗЫКУ У НАС</h2>
                        <div class="separator-line mt-14">
                            <img class="me-1" src="/images/shape/line-s2.png" alt="Images">
                            <img src="/images/shape/line-s1.png" alt="Images">
                        </div>
                        <div class="desc">
                            <p class="mt-21">ПРОВЕРКА УРОВНЯ И ПРОБНОЕ ЗАНЯТИЕ СОВЕРШЕННО БЕСПЛАТНО</p>
                        </div>
                    </div>
                </div>
            </div>
            <div class="row icon-box-style1">
                <div class="col-md-6 col-lg-4" data-aos="fade-up" data-aos-duration="1100" v-for="(service, index) in services" :key="index">
                    <ServiceItem :service="service" />
                </div>
            </div>
        </div>
        <div class="layer-shape">
            <img class="layer-shape-one" src="/images/shape/6.png" alt="shape">
            <img class="layer-shape-two" src="/images/shape/7.png" alt="shape">
        </div>
    </section>
</template>

<script>
    export default {
        data() {
            return {
                services: [
                    {
                        icon: "/images/icons/s1.png",
                        title: "98,8% реальный результат   ",
                        desc: "Мы регулярно проводим конроль качества преподавания и мониторинг полученных знаний."
                    },
                    {
                        icon: "/images/icons/s2.png",
                        title: "Утренние, дневные, вечерние группы",
                        desc: "Каждому студенту мы поможем подобрать наиболее подходящее время занятий"
                    },
                    {
                        icon: "/images/icons/s3.png",
                        title: "Доступные цены",
                        desc: "Цены на обучение в нашей школе начинаются с 990 сом за месяц"
                    },
                    {
                        icon: "/images/icons/s4.png",
                        title: "Компенсация занятий при пропуске",
                        desc: "Если Вы пропустили занятия, мы компенсируем их, добавив дополнительно к курсу обучения"
                    },
                    {
                        icon: "/images/icons/s5.png",
                        title: "Занятия в мини-группах",
                        desc: "Мы проводим занятия в группах до 12 человек, благодаря чему каждому уделяется достаточно внимания"
                    },
                    {
                        icon: "/images/icons/s6.png",
                        title: "Быстрый результат - за 1 месяц",
                        desc: "Вам не придется ждать 4-6 месяцев, пока вы что-то сможете рассказать. Уже на первом занятии вы будете говорить. Через 1 месяц сможете общаться в рамках простых времен!"
                    },
                ]
            }
        },
    };
</script>