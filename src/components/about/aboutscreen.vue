<template>
    <div class="container">
        <div class="row py-5 align-items-center">
          <div class="col-md-4 text-center">
                <img class="profileimg" :src="maindata1.imgUrl" alt="">
            </div>
            <div class="col-md-8">
                <p>{{maindata1.about}}</P>
            </div>
        </div>
        </div>
</template>
<script>
import maindata from '@/assets/data/main.json'
    export default {
        name:'AboutHome',
        data:()=>({
            maindata1:maindata
        })
    }
</script>

