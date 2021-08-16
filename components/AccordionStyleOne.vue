<template>
    <div class="accordion">
        <b-card no-body>
            <b-card-header header-tag="header">
                <b-button block v-b-toggle.accordion-1 class="accordion-button">
                    <span class="icon-box">
                        <i class="icon icofont-plus"></i>
                        <i class="icon icofont-minus"></i>
                    </span>
                    Логика вместо сотен правил
                </b-button>
            </b-card-header>
            <b-collapse id="accordion-1" visible accordion="my-accordion">
                <b-card-body>
                    <b-card-text>
                        Вся грамматика дается в виде компактной и логичной системы. Вместо сотен правил – 4 логические модели, позволяющие строить ЛЮБОЕ предложение на английском. Понятные схемы и модели для легкого усвоения материала.
                    </b-card-text>
                </b-card-body>
            </b-collapse>
        </b-card>
        <b-card no-body>
            <b-card-header header-tag="header">
                <b-button block v-b-toggle.accordion-2 class="accordion-button">
                    <span class="icon-box">
                        <i class="icon icofont-plus"></i>
                        <i class="icon icofont-minus"></i>
                    </span>
                   Запоминание через ассоциации и контекст
                </b-button>
            </b-card-header>
            <b-collapse id="accordion-2" visible accordion="my-accordion">
                <b-card-body>
                    <b-card-text>
                        Мы предлагаем современную технологию запоминания лексики через контекст или прямые ассоциации, минуя перевод на русский. Благодаря этому методу преподавания слово оказывается связано с конкретным образом, и так его намного проще выучить.
                    </b-card-text>
                </b-card-body>
            </b-collapse>
        </b-card>
        <b-card no-body>
            <b-card-header header-tag="header">
                <b-button block v-b-toggle.accordion-3 class="accordion-button">
                    <span class="icon-box">
                        <i class="icon icofont-plus"></i>
                        <i class="icon icofont-minus"></i>
                    </span>
                   Поддержка памяти в течение всего курса
                </b-button>
            </b-card-header>
            <b-collapse id="accordion-3" visible accordion="my-accordion">
                <b-card-body>
                    <b-card-text>
                        Система интервальных повторений помогает сохранить знания в активной долговременной памяти. График повторений строится с учетом психологических особенностей механизмов запоминания, поэтому вы запоминаете материал надолго.
                    </b-card-text>
                </b-card-body>
            </b-collapse>
        </b-card>
        <b-card no-body>
            <b-card-header header-tag="header">
                <b-button block v-b-toggle.accordion-4 class="accordion-button">
                    <span class="icon-box">
                        <i class="icon icofont-plus"></i>
                        <i class="icon icofont-minus"></i>
                    </span>
                   Развитие коммуникативных навыков с помощью игр и тренингов
                </b-button>
            </b-card-header>
            <b-collapse id="accordion-4" visible accordion="my-accordion">
                <b-card-body>
                    <b-card-text>
Справиться с языковым барьером помогут более 1 000 разнообразных игр и тренингов. Постоянная практика научит вас хорошо понимать устную речь и уверенно говорить самим, а также подготовит к реальным ситуациям общения.                    </b-card-text>
                </b-card-body>
            </b-collapse>
        </b-card>
    </div>
</template>