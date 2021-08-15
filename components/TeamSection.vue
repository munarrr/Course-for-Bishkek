<template>
    <section class="team-area">
        <div class="container">
            <div class="row">
                <div class="col-lg-8 m-auto">
                    <div class="section-title text-center" data-aos="fade-up" data-aos-duration="1000">
                        <h2 class="title">We’ve Awesome Team</h2>
                        <div class="separator-line mt-14">
                            <img class="me-1" src="/images/shape/line-s2.png" alt="Images">
                            <img src="/images/shape/line-s1.png" alt="Images">
                        </div>
                        <div class="desc">
                            <p class="mt-21">Lorem Ipsum is simply dummy text of the printing and typesetting industry has been <br>the industry's standard dummy text ever since the printer took</p>
                        </div>
                    </div>
                </div>
            </div>
            <div class="row">
                <div class="col-lg-12">
                    <div class="team-slider-content" data-aos="fade-up" data-aos-duration="1200">
                        <div class="team-slider-container">
                            <swiper :options="swiperOptions">
                                <div class="swiper-slide team-member">
                                    <div class="thumb">
                                        <img src="/images/team/1.jpg" alt="Image">
                                    </div>
                                    <div class="content">
                                        <div class="member-info">
                                            <div class="separator-line">
                                                <img src="/images/shape/line-s1.png" alt="Images">
                                            </div>
                                            <h4 class="name">Hosea Steiner</h4>
                                            <h6 class="designation">UI/UX Designer</h6>
                                            <!-- Start Progress Item -->
                                            <div class="progress-item">
                                                <div class="progress-line">
                                                    <div class="progress-bar-line" style="width: 75%">
                                                        <span class="percent">75%</span>
                                                    </div>
                                                </div>
                                                <div class="progress-info">
                                                    <span class="title">Professional Skill</span>
                                                </div>
                                            </div>
                                        </div>
                                    </div>
                                    <div class="shape-style">
                                        <img class="shape-style1" src="/images/shape/8.png" alt="Image">
                                        <img class="shape-style2" src="/images/shape/9.png" alt="Image">
                                        <img class="shape-style3" src="/images/shape/10.png" alt="Image">
                                    </div>
                                </div>
                                <div class="swiper-slide team-member">
                                    <div class="thumb">
                                        <img src="/images/team/2.jpg" alt="Image">
                                    </div>
                                    <div class="content">
                                        <div class="member-info">
                                            <div class="separator-line">
                                                <img src="/images/shape/line-s1.png" alt="Images">
                                            </div>
                                            <h4 class="name">Rosario Matthew</h4>
                                            <h6 class="designation">Web Developer</h6>
                                            <!-- Start Progress Item -->
                                            <div class="progress-item">
                                                <div class="progress-line">
                                                    <div class="progress-bar-line" style="width: 90%">
                                                        <span class="percent">90%</span>
                                                    </div>
                                                </div>
                                                <div class="progress-info">
                                                    <span class="title">Professional Skill</span>
                                                </div>
                                            </div>
                                        </div>
                                    </div>
                                    <div class="shape-style">
                                        <img class="shape-style1" src="/images/shape/8.png" alt="Image">
                                        <img class="shape-style2" src="/images/shape/9.png" alt="Image">
                                        <img class="shape-style3" src="/images/shape/10.png" alt="Image">
                                    </div>
                                </div>
                                <div class="swiper-slide team-member">
                                    <div class="thumb">
                                        <img src="/images/team/3.jpg" alt="Image">
                                    </div>
                                    <div class="content">
                                        <div class="member-info">
                                            <div class="separator-line">
                                                <img src="/images/shape/line-s1.png" alt="Images">
                                            </div>
                                            <h4 class="name">Tyson Holiday</h4>
                                            <h6 class="designation">Digital Marketer</h6>
                                            <!-- Start Progress Item -->
                                            <div class="progress-item">
                                                <div class="progress-line">
                                                    <div class="progress-bar-line" style="width: 80%">
                                                        <span class="percent">80%</span>
                                                    </div>
                                                </div>
                                                <div class="progress-info">
                                                    <span class="title">Professional Skill</span>
                                                </div>
                                            </div>
                                        </div>
                                    </div>
                                    <div class="shape-style">
                                        <img class="shape-style1" src="/images/shape/8.png" alt="Image">
                                        <img class="shape-style2" src="/images/shape/9.png" alt="Image">
                                        <img class="shape-style3" src="/images/shape/10.png" alt="Image">
                                    </div>
                                </div>
                            </swiper>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>
</template>

<script>
    export default {
        data() {
            return {
                swiperOptions: {
                    speed: 1500,
                    slidesPerView: 3,
                    centeredSlides: true,
                    spaceBetween : 30,
                    loop: true,
                    autoplay: {
                        delay: 3000,
                        disableOnInteraction: false,
                    },
                    breakpoints: {
                        992:{
                            slidesPerView : 3
                        },
                        768:{
                            slidesPerView : 2,
                            centeredSlides: false
                        },
                        0:{
                            slidesPerView : 1
                        }
                    }
                }
            }
        },
    };
</script>