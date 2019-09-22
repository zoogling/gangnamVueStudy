<template>
    <v-container>
        <v-btn @click="snack('top')">
         클릭
        </v-btn>
        <v-snackbar v-model="snackbar" :top="top" :bottom="bottom" :left="left" :right="right" :timeout="timeout">
            짜란
            <v-btn @click="snackbar = false">
                <v-icon>clear</v-icon>
            </v-btn>
        </v-snackbar>
    </v-container>
</template>

<script>
    export default {
        data: () => ({
            top: false,
            bottom: false,
            left: false,
            right: false,
            timeout: 6000,
            snackbar: false,
        }),
        methods: {
            snack(...args) {
                this.top = false;
                this.bottom = false;
                this.left = false;
                this.right = false;
                for (const loc of args) {
                    this[loc] = true
                }
                this.snackbar = true
            }
        }
    }
</script>