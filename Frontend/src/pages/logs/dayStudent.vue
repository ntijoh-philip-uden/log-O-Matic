<template>
    <v-container class="spacing-playground pa-8">
        <v-card
        class="mx-auto"
        elevation="8"
        max-width="448"
        rounded="lg"
        >
            <v-card-text class="text-medium-emphasis font-weight-bold justify-center align-center fill-height d-flex text-h5">
                Monday Week 48
            </v-card-text>
            <v-radio-group inline class="d-flex justify-center align-center ">
                <v-radio label="One at a Time" value="one" class="mr-4"></v-radio>
                <v-radio label="All at Once" value="two"></v-radio>
            </v-radio-group>
            <v-carousel
                height="80"
                hide-delimiters
            >
                <v-carousel-item>
                <v-sheet
                    height="100%"
                >
                    <v-card-text class="d-flex fill-height justify-center align-center">
                        1
                    </v-card-text>
                </v-sheet>
                </v-carousel-item>
                <v-carousel-item>
                <v-sheet
                    height="100%"
                >
                    <v-card-text class="d-flex fill-height justify-center align-center">
                        2
                    </v-card-text>
                </v-sheet>
                </v-carousel-item>
                <v-carousel-item>
                <v-sheet
                    height="100%"
                >
                    <v-card-text class="d-flex fill-height justify-center align-center">
                        3
                    </v-card-text>
                </v-sheet>
                </v-carousel-item>
            </v-carousel>
        </v-card>
        <v-card
        class="mx-auto mt-8"
        elevation="8"
        max-width="800"
        rounded="lg"
        >

            <v-container>
                <v-card 
                    width="100%"
                    class="border-b-lg pa-2"
                >
                    <v-card-title>
                        Vad har du gjort under dagen?
                    </v-card-title>
                    <v-card-text>
                        ed ut perspiciatis unde omnis iste natus error sit voluptatem accusantium doloremque laudantium, totam rem aperiam, eaque ipsa quae ab illo inventore
                    </v-card-text>
                </v-card>

                <v-card 
                    width="100%"
                    class="border-b-lg pa-2"
                >
                    <v-card-title>
                        Vad har du lärt dig?
                    </v-card-title>
                    <v-card-text>
                        ed ut perspiciatis unde omnis iste natus error sit voluptatem accusantium doloremque laudantium, totam rem aperiam, eaque ipsa quae ab illo inventore
                    </v-card-text>
                </v-card>

                <v-card 
                    width="100%"
                    class="border-b-lg pa-2"
                >
                    <v-card-title>
                        Vad förstod du inte / Vilka frågor har du inte fått svar på?
                    </v-card-title>
                    <v-card-text>
                        ed ut perspiciatis unde omnis iste natus error sit voluptatem accusantium doloremque laudantium, totam rem aperiam, eaque ipsa quae ab illo inventore
                    </v-card-text>
                </v-card>

                <v-card 
                    width="100%"
                    class="border-b-lg pa-2"
                >
                    <v-card-title>
                        Vad vill du lära dig mer om?
                    </v-card-title>
                    <v-card-text>
                        ed ut perspiciatis unde omnis iste natus error sit voluptatem accusantium doloremque laudantium, totam rem aperiam, eaque ipsa quae ab illo inventore
                    </v-card-text>
                </v-card>
            </v-container>

            <v-timeline>
                <v-timeline-item size="large">
                <template v-slot:icon>
                    <v-avatar image="https://i.pravatar.cc/64"></v-avatar>
                </template>
                <template v-slot:opposite>
                    <span>Tus eu perfecto</span>
                </template>
                <v-card class="elevation-2">
                    <v-card-title class="text-h5">
                    Lorem ipsum
                    </v-card-title>
                    <v-card-text>Lorem ipsum dolor sit amet, no nam oblique veritus. Commune scaevola imperdiet nec ut, sed euismod convenire principes at. Est et nobis iisque percipit, an vim zril disputando voluptatibus, vix an salutandi sententiae.</v-card-text>
                </v-card>
                </v-timeline-item>
            </v-timeline>            
            
        </v-card>

    </v-container>
</template>

<script>
    export default {
        
    }
</script>

<style lang="scss" scoped>

</style>