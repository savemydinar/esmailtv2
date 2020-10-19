<template>
  <div>
  
    <section class="section">
      <div class="container">
        <feb-alive>
          <router-view></router-view>
        </feb-alive>
        
      </div>
    </section>
    <APlayer />
  </div>
</template>

<script>


import APlayer from "./common/APlayer";
export default {
  data: function () {
    return {};
  },
  components: {
    
    APlayer
  },
  methods: {},
};
</script>
