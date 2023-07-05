<template>
 <div>
   <banner-vue/>
    <div class="main-container">
    <h1>Monte seu Hambúrguer:</h1>  
    </div>
    <burger-form-vue/>
  </div>
</template>

<script>
import BannerVue from '../components/Banner.vue'
import BurgerFormVue from '../components/BurgerForm.vue'

export default {
  name: 'HomeVue',
  components: {
    BannerVue,
    BurgerFormVue
    
  }
}
</script>
