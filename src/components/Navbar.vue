<template>
    <v-app-bar app color="#eeeeee" dark>
        <v-btn icon  color="#000000">
            <v-icon>mdi-magnify</v-icon>
        </v-btn>
        <v-divider vertical class="ml-1 mr-3"></v-divider>
        <v-btn icon color="#000000">
            <v-icon>mdi-menu</v-icon>
        </v-btn>
        <v-toolbar-title style="color:#000000">
            <span class="caption">Select</span><br>Category
        </v-toolbar-title>
        <v-divider vertical class="ml-5"></v-divider>
        <div  style="position:absolute; margin-left=auto; margin-right: =auto; left:0; right: 0; text-align:center; color:#000000 ">
        <h4 >Shoes Game</h4>
        </div>
        <v-spacer></v-spacer>
        <v-divider vertical></v-divider>
        <v-btn icon class="mx-1" color="#000000">
            <v-icon>mdi-account-outline</v-icon>
        </v-btn>
        <v-divider vertical></v-divider>
        <v-btn icon class="mx-1" color="#000000">
            <v-badge color="#D3D3D3" content="1">
                <v-icon>mdi-cart-outline</v-icon>
            </v-badge>
        </v-btn>
    </v-app-bar>

    </template>
     
    <script>
    export default{
    
    
    }
    
    </script>
    
    <style>
 
    .v-toolbar-title{
        font-size: 1rem !important;
        
    }
    .v-badge{
        font-size: 10px !important;
        height: 18px !important;
        min-width: 18px;
    }
    </style>