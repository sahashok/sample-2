<template>
<v-app id="Home">
  
    <v-container fluid>
        <div class="head">
<v-row>
    <v-col cols="5">
<div style="position: relative;">
<h1 class="text-grey">Hello,</h1>
<h1 class="text-grey">I'M Lara Elizabeth</h1>
<span class="text-grey">Web Designer & Developer</span><br/>
<v-dtn tile dark class="text-yellow mt-8" variant="outlined">Contact me</v-dtn>
</div>
    </v-col>
    <v-col cols="2">
        <div style="padding: absolute;z-index: 9999;bottom: 0;margin-left: auto;margin-right: auto;left: 0;">

        </div>
    </v-col>
</v-row>
        </div>
    </v-container>
</v-app>
</template>
<script>
export default {
    name: "HomeCom",

}
</script>

<style scoped>
.v-container{
    padding: 16px 0;
}
.head{
    position: relative;
    text-align: center;
    padding: 12px;
    margin-bottom: 6px;
    height: 400px;
    width: 100%;
    color: white;
}
.head:before{
    content: "";
    position: absolute;
    top: 0;
    left: 0;
    height: 100%;
    width: 50%;
    background: black;
    transform: skew(0deg, 6deg);
}
.head::after{ 
    content: "";
    position:absolute;
    top:0;
    right:0;
    height: 100%;
    width: 50%;
    background: black;
    transform: skew(0deg, -6deg);
}
.egg{
    display: block;
    margin-left: 100px;
    margin-top: 50px;
    width: 356px;
    height: 300px;
    background-color: white;
    border-radius: 50% 50% 50% 50% / 60% 60% 40% 0%;
}

</style>