<template>
    <v-content class="panel-container">
        <v-toolbar class="panel-toolbar">
            <v-toolbar-title>User Profile</v-toolbar-title>
            <div class="flex-grow-1"></div>
            <v-toolbar-items>
                <v-text-field>

                </v-text-field>
                <v-btn icon>
                    <v-icon>mdi-view-dashboard</v-icon>
                </v-btn>
                <v-btn icon>
                    <v-icon>mdi-bell</v-icon>
                </v-btn>
                <v-btn icon>
                    <v-icon>mdi-account</v-icon>
                </v-btn>
            </v-toolbar-items>
        </v-toolbar>

        <v-layout class="min-height">
               <v-col class="col-8">
                    <v-card>
                        <p>hi</p>
                    </v-card>
               </v-col>
               <v-col class="col-4">

               </v-col>
        </v-layout>

    </v-content>
</template>

<script>
    export default {
        name: "Panel.vue"
    }
</script>

<style lang="scss" scoped>
    .panel-container {
        background: #eeeeee;
        .panel-toolbar {
            background: #eeeeee;
        }
    }
    .min-height {
        min-height: 100%;
    }
</style>