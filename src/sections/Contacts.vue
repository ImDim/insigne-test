<template lang="pug">
section.section.contacts
    .site-wrapper
        h2.section__header
            |Где купить

        p.section__desc
            |В московском магазине на улице Строителей, 6, корпус 4. Или 
            a(href="#") у наших партнёров.
            br
            |Магазин работает с 8:00 до 20:00 с понедельника по воскресенье.

        .contacts__map
</template>

<script>
export default {
  name: 'Contacts'
}
</script>

<style scoped lang="scss">
    @import '~@/styles/sections/contacts';
</style>