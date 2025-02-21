<template>
    <v-card class="mx-auto" elevation="24">
<v-container>

<v-carousel hide-delimiters>
    <v-carousel-item src="../public/image 1.jpg" cover> </v-carousel-item>
    <v-carousel-item src="../public/image 2.jpg" cover> </v-carousel-item>
    <v-carousel-item src="../public/image 3.jpg" cover> </v-carousel-item>
    <v-carousel-item src="../public/image 4.jpg" cover> </v-carousel-item>
</v-carousel>

</v-container>

    </v-card>
<v-container>
        <v-card class="mx-auto" elevation="24">car
            <v-container>
            <v-row>
                <v-col cols="12" md="4">
                    <v-card>
                        <v-card color="red">
                            <v-card-item>
                                <v-card-title>Burgers Menu</v-card-title>

                                <v-card-subtitle>Try out some of our Burgers!!</v-card-subtitle>
                            </v-card-item>
                            <v-img height="200px" src="public/Burger.jpg" cover ></v-img>

                            <v-card-text>
                            Prices starting from 870KSH=
                            </v-card-text>
                        </v-card>
                        <v-card color="blue">
                            <v-card-item>
                            <v-card-title>Milkshake Menu</v-card-title>

                            <v-card-subtitle>This are some of the milkshakes we offer!!</v-card-subtitle>
                            </v-card-item>
                            <v-img height="200px" src="public/Milkshake (1).jpg" cover ></v-img>

                            <v-card-text>
                            Prices starting from 250KSH=
                            </v-card-text>
                        </v-card>
                    </v-card>

                </v-col>

                <v-col cols="12" md="4">
                    <v-card>
                    <v-card color="yellow">
                    <v-card-item>
                    <v-card-title>Upcoming Events</v-card-title>

                    <v-card-subtitle>This are some of our upcoming events!!</v-card-subtitle>
                    </v-card-item>
                    <v-img height="200px" src="public/Event.jpg" cover ></v-img>

                    <v-card-text>
                    Book a Reservation!!
                    </v-card-text>
                    </v-card>
                    <v-card color="black">
                    <v-card-item>
                    <v-card-title>Upcoming Events</v-card-title>

                    <v-card-subtitle>Plan an event here!!</v-card-subtitle>
                    </v-card-item>
                    <v-img height="200px" src="public/Event 2.jpg" cover ></v-img>

                    <v-card-text>
                    Pricing depends on how large the event is
                    </v-card-text>
                    </v-card>
                </v-card>

                </v-col>

                <v-col cols="12" md="4">
                    <v-card>
                        <v-card color="orange">
                    <v-card-item>
                    <v-card-title>Promotions</v-card-title>

                    <v-card-subtitle>Welcome to our Thanks-Giving party</v-card-subtitle>
                    </v-card-item>
                    <v-img height="200px" src="public/Promotion.jpg" cover ></v-img>

                    <v-card-text>
                    25% Off on any reservation before 25th October
                    </v-card-text>
                        </v-card>
                        <v-card color="teal">
                    <v-card-item>
                    <v-card-title>Promotions</v-card-title>

                    <v-card-subtitle> </v-card-subtitle>
                    </v-card-item>
                    <v-img height="200px" src="public/Promotion 2.jpg" cover ></v-img>

                    <v-card-text>
                    Plan early!!
                    </v-card-text>
                        </v-card>
                    </v-card>

                </v-col>
            </v-row>
        </v-container>
        </v-card>
    </v-container>

    <v-container>
        <v-card class="mx-auto" elevation="24" color = "teal">
            <v-container>
                <v-row >
                    <v-col cols="12" md="4">
                        <v-card>
                            <v-card-item>
                                <v-card-title>Contact Us</v-card-title>
                            </v-card-item>
                            <v-card-text><v-icon icon="mdi-phone" /> 0712345678</v-card-text>
                            <v-card-text><v-icon icon="mdi-email" /> myrestaurant@example.com</v-card-text>
                            <v-card-text>Operating Hours: 10.00am - 10.00pm</v-card-text>
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
                    <v-col cols="12" md="4">
                        <v-card>
                            <v-card-item>
                            <v-card-title>Our Restaurant Locations</v-card-title>
                            </v-card-item>
                            <v-card-text>Madaraka</v-card-text>
                            <v-card-text>CBD</v-card-text>
                            <v-card-text>Langata</v-card-text>
                        </v-card>
                    </v-col>
                </v-row>
            </v-container>
        </v-card>
    </v-container>
</template>

<script setup>

</script>
