<template>
        <v-app-bar app dark flat class="px-12">
            <v-btn prepend-icon="mdi-check-circle">
                <template v-slot:prepend>
                    <v-icon color="yellow"></v-icon>
                </template>
                AHLAM
            </v-btn>
            <v-spacer></v-spacer>
            <v-btn @click="scroll('home')">Home</v-btn>
            <v-btn text @click="scroll('about')">About</v-btn>
            <v-btn text @click="scroll('portfollo')">Portfollo</v-btn>
            <v-btn text @click="scroll('services')">Services</v-btn>
            <v-btn text @click="scroll('page')">Page</v-btn>
            <v-btn text @click="scroll('blog')">Blog</v-btn>
            <v-btn text @click="scroll('contact')">contact</v-btn>


        </v-app-bar>
</template>
<script>
export default {
    name:"NavBar",
    methods: {
        scroll(refName) {
            const element = document.getElementById(refName);
            element.scrollIntoView({behavior: "smooth"});
        }
    }
}
</script>

<style>

</style>