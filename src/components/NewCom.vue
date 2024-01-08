<template>
    <div>
        <v-row cols="12">
                        <div class="egg">
                            <v-col cols="12" sm="6">
                                <img :src="require('@/assets/Image/asd8.jpg')" width="400px"/>
                            </v-col>


                            <v-col cols="12" ms="6">
                                <h5 class="text-pink mt-16">About Me</h5>
                                <div style="width: 120%">
                                    <v-slider v-model="slider2" color="yellow" label="track-color">
                                    </v-slider>
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
                            </v-col>
                        </div>
                    </v-row>
    </div>
</template>
<script>
export default {
    name: "NewCom",
}
</script>

