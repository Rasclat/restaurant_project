<template>
<v-card color="black" >
        <v-card-title>
            <div class="text-h3">About Us</div>
        </v-card-title>
</v-card>

    <v-card class="mx-auto" elevation="24">
        <v-container>

            <v-carousel hide-delimiters>
                <v-carousel-item src="../public/Restaurant.jpg" cover> </v-carousel-item>
                <v-carousel-item src="../public/image 2.jpg" cover> </v-carousel-item>
                <v-carousel-item src="../public/image 3.jpg" cover> </v-carousel-item>
                <v-carousel-item src="../public/image 4.jpg" cover> </v-carousel-item>
            </v-carousel>

        </v-container>

    </v-card>

    
    <v-container>
        <v-card class="mx-auto" elevation="24">
            <v-container>
                <v-card>
                    <v-card-title>Why should you choose us??</v-card-title>
                    <v-card-text>Every day, more than 11 million guests visit Sean John Combs restaurants around the world. And they do so because our restaurants are known for serving high-quality, great-tasting variety of foods. Founded in 1954, Sean John Combs Restaurant is the largest fast food chain in the world. Home of the Diddy. The famous burger is the DIDDY. The beef is flame-grilled which gives it its particular flavor. The original Home of the Diddy, our commitment to premium ingredients, signature recipes, and family-friendly dining experiences is what has defined our brand for more than 50 successful years. Have it your way!! Our burgers are made to order with fresh vegetables cut in the restaurant. Not only are there variety of burgers but also the tantzlizing Diddy Rib!! We have so much more to offer here!! Chech us out!!</v-card-text>
                </v-card>

                <v-card>
                    <v-card-title>In case of any query you can reach us through</v-card-title>
                    <v-row >
                    <v-col cols="12" md="4">
                        <v-card>
                            <v-card-item>
                                <v-card-title>Contact Us</v-card-title>
                            </v-card-item>
                            <v-card-text><v-icon icon="mdi-phone" /> 0712345678</v-card-text>
                            <v-card-text><v-icon icon="mdi-email" /> myrestaurant@example.com</v-card-text>
                        </v-card>
                    </v-col>

                        <v-col cols="12" md="4">
                        <v-card>
                            <v-card-item>
                            <v-card-title>Find us on our socials</v-card-title>

                            </v-card-item>
                            <v-card-text><v-icon icon="mdi-instagram" /> @Restaurant</v-card-text>
                            <v-card-text><v-icon icon="mdi-twitter" /> @Restaurant</v-card-text>
                            <v-card-text><v-icon icon="mdi-facebook" /> @Restaurant</v-card-text>
                        </v-card>
                    </v-col>
                    
                </v-row>
                </v-card>
            </v-container>
        </v-card>
    </v-container>
</template>

<script setup>

</script>