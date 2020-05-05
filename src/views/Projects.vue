<template>
    <div>
      <h2>My Projects</h2>
        <div class="row">
            <div class="col-md-4" >
                <div class="card p-3">
                    <projData/>
                </div>
            </div>
    </div>
    </div>
</template>
<script>
    import projData from '@/components/projects/proj'
    
export default {
    name:projcomp,
    components:{
        projData
    },
    data:()=>({
    }),
    methods:{

    }
}
</script>