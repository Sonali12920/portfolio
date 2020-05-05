<template>
  <div class="container">
    <div class="row">
      <div class="col-md-12">
        <HomeStartScreen/>
      </div>
    </div>

    <div class="row py-4">
      <div class="col-md-12">
        <SkillsComponent/>
      </div>
    </div>

    <div class="row py-4">
      <div class="col-md-12">
        <ProjectComponent/>
      </div>
    </div>

    <div class="row">
      <div class="col-md-12">
        <!-- <HomeComponent/> -->
      </div>
    </div>
    
    
  </div>
</template>

<script>
import HomeStartScreen from '@/components/home/homestartscreen'
import SkillsComponent from '@/components/home/skillset'
import ProjectComponent from '@/components/home/projects'

  export default {
    name:'HomeComponent23',
    components:{
      HomeStartScreen,
      SkillsComponent,
      ProjectComponent
    },
    data:()=>({

    }),
    methods:{

    }
  }
</script>