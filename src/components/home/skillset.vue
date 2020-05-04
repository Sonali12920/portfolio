<template>
    <div class="container" >
             <h1 style="text-align:center">Skills</h1>
        <div class="row">
            <div class="col-md-2 m-1 " v-for="(item,index) in mainData1.skills" :key="index">
                <div class="card">
                {{item}}
                </div>
        </div>
        </div>
    </div>
</template>

<script>
import maindata from '@/assets/data/main.json'
    export default {
        name:'Skillsets',
        data:()=>({
            mainData1: maindata
        }),
        methods:{

        }
    }
</script>

<style>
    .card{
        text-align: center;
        border: 0.5px solid black;
        border-radius: 5px;
    }
    .card:hover{
        background-color: black;
        color: white;
    }
    
</style>