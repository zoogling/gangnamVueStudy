<template>
    <v-app>
        <dashboard-nav></dashboard-nav>
        <dashboard-header v-if="false"></dashboard-header>
        <dashboard-panel></dashboard-panel>
    </v-app>
</template>

<script>
    import Nav from "../components/kang/layouts/Nav";
    import Panel from "../components/kang/layouts/Panel";
    import Header from "../components/kang/layouts/Header";

export default {
    layout: 'kangLayout',
    components: {
        'dashboard-nav': Nav,
        'dashboard-panel': Panel,
        'dashboard-header': Header
    },
    data(){
        return{
        }
    }
}
</script>

<style lang="scss" scoped>
    .app {
    }

</style>