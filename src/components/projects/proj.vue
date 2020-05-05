<template>
    <div>
      <h2>My Projects</h2>
        <div class="row">
            <div class="col-md-4" v-for="(item,index) in mainDataa.projects" :key="index">
                <div class="card p-3">
                    <p>{{item.title}}</p>
                    <p>{{item.des}}</p>
                    <a :href="item.link">Click Here</a>
                </div>
            </div>
    </div>
    </div>
</template>
<script>
    import maindata from '@/assets/data/main.json'
export default {
    name:projcomp,
    data:()=>({
          mainDataa: maindata
    }),
    methods:{

    }
}
</script>