<template><v-container>
    <v-card color="blue" >
        <v-card-title>
            <div class="text-h3">Our Menu</div>
        </v-card-title>
    </v-card>
</v-container>

    <v-container>
        <v-card class="mx-auto" elevation="24">
            <v-container>
            <v-row>
                <v-col cols="12" md="4" v-for="item in menuItems" :key=item>
                    <v-card>
                        <v-card color="black">
                            <v-card-item>
                                <v-card-title>{{ item.name }}</v-card-title>

                                <v-card-subtitle>{{ item.description }}</v-card-subtitle>
                            </v-card-item>
                            <v-img height="200px" :src="item.image" cover ></v-img>

                            <v-card-text>{{ item.price }}
                                <v-btn color="teal" variant="tonal" @click="addToOrder(item)">
                                Order
                                </v-btn>
                            </v-card-text>


                        </v-card>
                    </v-card>
                </v-col>
            </v-row>
            </v-container>
        </v-card>
    </v-container>
    <v-container>
        <v-card color="blue" >
            <v-card-title>
                <div class="text-h6">Current order: {{totalOrderAmount}}</div>
            </v-card-title>
        </v-card>
    </v-container>
    <v-container>
        <v-card class="mx-auto" elevation="24">
            <v-container>
                <v-row>
                    <v-col cols="12" md="4" v-for="item in orderItems" :key=item>
                        <v-card color="yellow">
                            <v-card-item>
                            <v-card-title>{{ item.name }}</v-card-title>

                            <v-card-subtitle>{{ item.description }}</v-card-subtitle>
                            </v-card-item>
                            <v-img height="200px" :src="item.image" cover ></v-img>

                            <v-card-text>{{ item.price }}</v-card-text>
                        </v-card>
                        </v-col>
                </v-row>
            </v-container>
        </v-card>
    </v-container>

</template>

<script setup>
const menuItems = [
    {
        name: "Chips",
        price: 200,
        description: "Best chips in town",
        size: "Large",
        offers: "None",
        image: "../public/Chips.jpg",
    },
    {
        name: "Sausage",
        price: 50,
        description: "Best sausages in town",
        size: "None",
        offers: "None",
        image: "../public/Sausages.jpg",
    },
    {
        name: "Burger",
        price: 950,
        description: "Best burgers in town",
        size: "None",
        offers: "None",
        image: "../public/Burger 2.jpg"
    },
    {
        name: "Ribs",
        price:1050,
        description: "Best ribs in town",
        size: "None",
        offers: "None",
        image: "../public/Ribs.jpg",
    },
    {
        name: "Chapati",
        price: 35,
        description: "Best chapatis in town",
        size: "None",
        Offers: "None",
        image: "../public/Chapati.jpg",
    },
    {
        name: "Shawarma",
        price: 65,
        description: "Best shawarmas in town",
        size: "None",
        Offers: "None",
        image: "../public/Shawarma.jpg",
    }    
    ]

//manage the current state of order    
var orderItems =[]
var totalOrderAmount =0

function calculateTotalAmount(price){
    totalOrderAmount += price
}

function addToOrder(item){
    orderItems.push(item)
    calculateTotalAmount(item.price)
}

</script>