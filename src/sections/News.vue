<template lang="pug">
.site-wrapper
    ul.news-list
        li.news-list__item
            a(href="#").news-list__link
                article.news.news--sale
                    h3.news__title
                        |Распродажа

                    p.news__text
                        |Скидка 50% на все модели 
                        |с подошвой Vibram®

        li.news-list__item
            a(href="#").news-list__link
                article.news.news--start
                    h3.news__title
                        |Битцевская фабрика

                    img(src="@/assets/images/gallery/timberland.png", alt="timberland").news__img

                    p.news__text
                        |Старт продаж 1 августа 19:00
</template>

<script>
export default {
  name: 'News'
}
</script>

<style scoped lang="scss">
    @import '~@/styles/sections/news';
</style>