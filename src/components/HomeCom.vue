<template>
    <v-app id="Home">
        <div class="head">
            <v-container fluid>
                <v-row>
                    <v-col cols="5">
                        <div style="position: relative;">
                            <h1 class="text-grey">Hello,</h1>
                            <h1 class="text-white">I'M Lara Elizabeth</h1>
                            <span class="text-grey">Web Designer & Developer</span><br />
                            <v-btn tile dark class="text-yellow mt-8" variant="outlined">Contact me</v-btn>
                        </div>
                    </v-col>
                    <v-col cols="2">
                        <v-icon style="margin-right: 10%; margin-top: 130%;"
                            class="text-h4">mdi-chevron-double-down</v-icon>
                    </v-col>
                    <v-col cols="5">
                        <v-img :src="require('@/assets/Image/asdf.png')" style="z-index:10" contain
                            max-height="300"></v-img>
                    </v-col>
                </v-row>
                <v-col cols="12" class="mt-16" id="about">
                    <v-row>
                        <v-col cols="12" sm="6">
                            <h5 class="text-pink mt-16">About Me</h5>
                            <div style="width: 100%">
                                <v-slider v-model="slider2" color="yellow" label="track-color"> </v-slider>
                            </div>
                            <img :src="require('@/assets/Image/asd8.jpg')" width="450px" height="300px" />
                        </v-col>
                        <v-col cols="12" sm="6">
                            <!-- <img :src="require('@/assets/Image/asd8.jpg')" width="400px"/> -->
                            <div class="text-center mt-4">
                                <h1 class="text-green">what we Do</h1>
                                <div style="width:120px; margin: 0 auto;">
                                    <v-slider v-model="slider2" color="yellow" label="crack-color"></v-slider>
                                </div>
                            </div>
                            <h4 class="text-green mt-n4">I am a Creative Web Design</h4>
                            <h4 class="text-blue">And Developer</h4>
                            <p class="text-grey">
                                Lorem ipsum dolor sit, amet consectetur adipising elit.
                                Aspernatur, uliam perspiciatis fugiat temporibus laboriosam
                                accusamus tempora repellendus sequi sed cum dolorum vero est.
                                Placeat dicta architecto relciendis est venlam. Unde.
                            </p>
                            <br />
                            <p class="text-grey">
                                Lorem ipsum dolor sit, amet consectetur adipising elit.
                                Aspernatur, uliam perspiciatis fugiat temporibus laboriosam
                                accusamus tempora repellendus sequi sed cum dolorum vero est.
                                Placeat dicta architecto relciendis est venlam. Unde.
                            </p>
                            <v-btn tile dark color="yellow" class="mt-4">
                                Download Resume
                            </v-btn>
                            <div class="child">
                                <v-btn icon="mdi-account-child-circle" color="yellow" class="text-blue"></v-btn>
                            </div>
                        </v-col>
                    </v-row>
                    <!-- <v-col cols="12" class="mt-16" id="Portfollo"> -->
                    <v-row cols="12" align="center" style="margin-left: 35%;">
                        <v-col cols="2">
                            <div class="child">
                                <v-btn icon="mdi-account-child-circle" color="yellow" class="text-blue text-h5"></v-btn>
                            </div>
                            <!-- <v-icon class="text-blue text-h3">mdi-account</v-icon> -->
                            <h4 class="text-green">Paras Kumar sah </h4>
                        </v-col>
                        <v-col cols="2">
                            <div class="child">
                                <v-btn icon="mdi-account-child-circle" color="yellow" class="text-blue text-h5"></v-btn>
                            </div>
                            <h4 class="text-green">Paras Kumar sah </h4>
                        </v-col>
                        <v-col cols="2">
                            <div class="child">
                                <v-btn icon="mdi-account-child-circle" color="yellow" class="text-blue text-h5"></v-btn>
                            </div>
                            <h4 class="text-green">Paras Kumar sah </h4>
                        </v-col>
                    </v-row>
                    <v-row align="center">
                        <v-col cols="4">
                            <img :src="require('@/assets/Image/asd8.jpg')" width="300px" height="300px" />
                            <h4 class="text-blue text-h4"><b>Web Design</b></h4>
                            <p class="text-grey">Lorem, Ipsum dolor sit amet<br />
                                consectetur adipisicing<br />
                                consectetur adipis<br /> </p>
                        </v-col>
                        <v-col cols="4">
                            <img :src="require('@/assets/Image/asd8.jpg')" width="300px" height="300px" />
                            <h4 class="text-blue text-h4"><b>App Design</b></h4>
                            <p class="text-grey">Lorem, Ipsum dolor sit amet<br />
                                consectetur adipisicing<br />
                                consectetur adipis<br /> </p>
                        </v-col>
                        <v-col cols="4">
                            <img :src="require('@/assets/Image/asd8.jpg')" width="300px" height="300px" />
                            <h4 class="text-blue text-h4"><b>Photography</b></h4>
                            <p class="text-grey">Lorem, Ipsum dolor sit amet<br />
                                consectetur adipisicing<br />
                                consectetur adipis<br /> </p>
                        </v-col>
                    </v-row>
                    <v-row align="center">
                        <v-col cols="4">
                            <img :src="require('@/assets/Image/asd3.jpg')" width="300px" height="300px" />
                        </v-col>
                        <v-col cols="4">
                            <img :src="require('@/assets/Image/asd3.jpg')" width="300px" height="300px" />
                        </v-col>
                        <v-col cols="4">
                            <img :src="require('@/assets/Image/asd3.jpg')" width="300px" height="300px" />
                        </v-col>
                        <v-col cols="4">
                            <img :src="require('@/assets/Image/asd11.jpg')" width="300px" height="300px" />
                        </v-col>
                        <v-col cols="4">
                            <img :src="require('@/assets/Image/asd11.jpg')" width="300px" height="300px" />
                        </v-col>
                        <v-col cols="4">
                            <img :src="require('@/assets/Image/asd11.jpg')" width="300px" height="300px" />
                        </v-col>
                        <v-col v-for="n in 3" :key="n" cols="4">
                            <img :src="require('@/assets/Image/asd2.jpg')" width="300px" height="300px" />
                        </v-col>
                        <v-col v-for="n in 3" :key="n" cols="4">
                            <img :src="require('@/assets/Image/asd7.jpg')" width="300px" height="300px" />
                        </v-col>
                    </v-row>
                </v-col>
                <v-row align="center">
                    <v-col cols="12">
                        <v-btn color="yellow" class=" ma-4">ALL</v-btn>
                        <v-btn color="grey" class="ma-4">WED DESIGN</v-btn>
                        <v-btn color="grey" class="ma-4">FRONT DESIGN</v-btn>
                        <v-btn color="grey" class="ma-4">PHOTOGRAPHY</v-btn>
                        <v-btn color="grey" class="ma-4">ILLUSTRATION</v-btn>
                    </v-col>
                </v-row>
                <v-row>
                    <v-col cols="4">
                        <img :src="require('@/assets/Image/asd11.jpg')" width="300px" height="300px" />
                        <v-card class="mx-auto my-8" max-width="344" elevation="16">
                            <v-icon color="green text-h3">mdi-account-child-circle</v-icon>
                            <h3 class="text-black">We provide you the best</h3>
                            <h4 class="text-grey">By AAE EdeaPro 106 Sep 2020</h4>
                            <p class="text-black"> 
                                Lorem ipsum dolor sit amet consectetur<br/>
                                adipisicing elit Sit tem saepe sapiente<br/>
                                deleniti. odio non laborum fuga.
                            </p>
                        </v-card>
                    </v-col>
                    <v-col cols="4">
                        <img :src="require('@/assets/Image/asd7.jpg')" width="300px" height="300px" />
                        <v-card class="mx-auto my-8" max-width="344" elevation="16">
                            <v-icon color="green text-h3">mdi-account-child-circle</v-icon>
                            <h3 class="text-black">We provide you the best</h3>
                            <h4 class="text-grey">By AAE EdeaPro 106 Sep 2020</h4>
                            <p class="text-black"> 
                                Lorem ipsum dolor sit amet consectetur<br/>
                                adipisicing elit Sit tem saepe sapiente<br/>
                                deleniti. odio non laborum fuga.
                            </p>
                        </v-card>
                    </v-col>
                    <v-col cols="4">
                        <img :src="require('@/assets/Image/asd8.jpg')" width="300px" height="300px" />
                        <v-card class="mx-auto my-8" max-width="344" elevation="16">
                            <v-icon color="green text-h3">mdi-account-child-circle</v-icon>
                            <h3 class="text-black">We provide you the best</h3>
                            <h4 class="text-grey">By AAE EdeaPro 106 Sep 2020</h4>
                            <p class="text-black"> 
                                Lorem ipsum dolor sit amet consectetur<br/>
                                adipisicing elit Sit tem saepe sapiente<br/>
                                deleniti. odio non laborum fuga.
                            </p>
                        </v-card>
                    </v-col>
                </v-row>
                <v-row align="center">
                    <v-col>
                        <v-btn color="yellow">SUBMIT NOW</v-btn>
                    </v-col>
                </v-row>
            </v-container>
        </div>
    </v-app>
</template>
<script>
export default {

    name: "HomeCom"
};
</script>

<style scoped>
.v-container {
    padding: 16px 0;
}

.head {
    position: relative;
    text-align: center;
    padding: 12px;
    margin-bottom: 6px;
    height: 400px;
    width: 100%;
    color: white;
}

.head:before {
    content: "";
    position: absolute;
    top: -13%;
    left: 0;
    height: 100%;
    width: 50%;
    background: black;
    transform: skew(0deg, 6deg);
}

.head::after {
    content: "";
    position: absolute;
    top: -13%;
    right: 0;
    height: 100%;
    width: 50%;
    background: black;
    transform: skew(0deg, -6deg);
}

.egg {
    display: block;
    margin-left: 100px;
    margin-top: 50px;
    width: 356px;
    height: 300px;
    background-color: white;
    border-radius: 50% 50% 50% 50% / 60% 60% 40% 40%;
}

.first {
    width: 100%;
    height: 280px;
    text-align: center;
    padding: 2rem 2rem;
}

.child {
    display: inline-block;
    padding: 2rem 1rem;
    vertical-align: center;
    text-align: center;
    margin-right: 8px;
}

.imgHover {
    padding: 0 200px;

}

.pre {
    width: 100%;
    height: 380px;
    text-align: center;
    padding: 0 200px;
    background-color: aliceblue;
}

.hire {
    width: 100%;
    height: 200px;
    padding: 0 200px;
    background-color: #f5f5f5;
    margin-top: -24px;
}
</style>