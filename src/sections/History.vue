<template lang="pug">
section.section.section--colored-yellow.section-history
    .site-wrapper
        h2.section__header
            |Делаем валенки с 1897 года

        .flex.jc-start.ai-start
            .section-history__inner.section-history__inner--wide
                p.section__desc
                    |Совмещаем русские традиции и современные технологии 
                    |производства тёплой обуви.

                img(src="@/assets/images/gallery/2.png", alt="").section-history__img

            .section-history__inner.flex
                .section-history__founder
                    img(src="@/assets/images/gallery/15.png", alt="Петр Крабиусиков, 1902 год").section-history__founder-img

                    span.section-history__founder-text
                        |Портрет основателя фабрики
                        |Петра Крабиусикова, 1902 год

                p.section-history__text
                    b Каждую пару валенок делаем вручную,
                    br
                    |Это наша философия и гарантия качества. 
                    |На коробке с валенками 
                    |всегда есть имя мастера, 
                    |который их сделал.

        .flex.jc-start.ai-start
            .section-history__item
                img(src="@/assets/images/gallery/3.png", alt="Используем шерсть мулана").section-history__img

                p.section-history__text
                    b Используем шерсть мулана, 
                    |она теплее 
                    |и легче, чем популярная шерсть Вятка. 
                    |Шерсть мулана сохраняет тепло при 
                    |−35˚, дышит и принимает форму стопы

            .section-history__item
                img(src="@/assets/images/gallery/4.png", alt="Используем стельки «Адипрен»").section-history__img

                p.section-history__text
                    b Используем стельки «Адипрен» 
                    | с эффектом массажа: через 4 часа ноги 
                    |не устанут. Такие же стельки 
                    |используют в беговых кроссовках. 
</template>

<script>
export default {
  name: 'History'
}
</script>

<style scoped lang="scss">
    @import '~@/styles/sections/history';
</style>