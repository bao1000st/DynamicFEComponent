<template>
    <div id="app" class="container">
        <the-header />
        <the-navigation />
        <the-services />
        <the-details />
        <the-features />
        <the-reviews />
        <the-contact />
        <the-footer />

    </div>
</template>
  
<script>
import TheHeader from '@/components/header.vue'
import TheNavigation from '@/components/navigation.vue'
import TheServices from '@/components/services.vue'
import TheDetails from '@/components/details.vue'
import TheFeatures from '@/components/features.vue'
import TheReviews from '@/components/reviews.vue'
import TheContact from '@/components/contact.vue'
import TheFooter from '@/components/footer.vue'

export default {
    name: 'app',
    components: {
        TheHeader,
        TheNavigation,
        TheServices,
        TheDetails,
        TheFeatures,
        TheReviews,
        TheContact,
        TheFooter
    }
}
</script>
  
<style lang="css">
#app {
    font-family: Avenir, Helvetica, Arial, sans-serif;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    text-align: center;
    color: #2c3e50;
    margin-top: 60px;
}

#header {
    font-family: Avenir, Helvetica, Arial, sans-serif;
    color: #2c3e50;
    font-size: 18px;
}

#navigation {
    font-family: Avenir, Helvetica, Arial, sans-serif;
    color: #2c3e50;
    font-size: 18px;
}

#services {
    font-family: Avenir, Helvetica, Arial, sans-serif;
    color: #2c3e50;
    font-size: 18px;
}

#details {
    font-family: Avenir, Helvetica, Arial, sans-serif;
    color: #2c3e50;
    font-size: 18px;
}

#features {
    font-family: Avenir, Helvetica, Arial, sans-serif;
    color: #2c3e50;
    font-size: 18px;
}

#reviews {
    font-family: Avenir, Helvetica, Arial, sans-serif;
    color: #2c3e50;
    font-size: 18px;
}

#contact {
    font-family: Avenir, Helvetica, Arial, sans-serif;
    color: #2c3e50;
    font-size: 18px;
}
</style>