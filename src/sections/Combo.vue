<template lang="pug">
section.section.section--colored-blue
    .site-wrapper
        h2.section__header
            |С чем носить

        p.section__desc
            |В этих валенках можно гулять 5—6 часов подряд. Массажная стелька — ноги не устанут.
            |Резиновая подошва защитит от холода

        .combo-grid.flex
            .combo-grid__col
                .combo-grid__block.combo-grid__block--wide
                    .image-block
                        img(src="@/assets/images/gallery/7.png", alt="С джинсами").image-block__img
                        span.image-block__caption
                            |С джинсами

                .combo-grid__block.combo-grid__block--wide
                    .image-block
                        img(src="@/assets/images/gallery/8.png", alt="C узкими брюками").image-block__img
                        span.image-block__caption
                            |C узкими брюками


            .combo-grid__col
                .combo-grid__block
                    .image-block
                        img(src="@/assets/images/gallery/9.png", alt="С пальто").image-block__img
                        span.image-block__caption
                            |С пальто

                .combo-grid__block
                    .image-block
                        img(src="@/assets/images/gallery/10.png", alt="C жилеткой").image-block__img.image-block__img--transformed
                        span.image-block__caption
                            |C жилеткой

                .combo-grid__block.combo-grid__block--wide
                    .image-block
                        img(src="@/assets/images/gallery/11.png", alt="Cо спортивными штанами").image-block__img.image-block__img--transformed
                        span.image-block__caption
                            |Cо спортивными штанами
</template>

<script>
export default {
  name: 'Combo'
}
</script>

<style scoped lang="scss">
    @import '~@/styles/sections/combo';
</style>