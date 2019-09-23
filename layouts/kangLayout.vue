<template>
    <v-col cols="12" class="app-layout">
        <nuxt/>
    </v-col>
</template>
<script>
import 'vuetify/dist/vuetify.min.css'
export default {

}
</script>

<style lang="scss">
    html, body {
        height: 100%;
        min-height: 100%;
    }
    .app-layout {
        height: 100%;
        padding: 0;
    }
    #__nuxt, #__layout {
        height: 100%;
    }

</style>