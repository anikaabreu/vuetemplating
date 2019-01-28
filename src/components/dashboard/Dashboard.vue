<template>
  <div class="dashboard">
    <div class="auth-wallpaper col-12">
      <div class="oblique"></div>
      <div class="auth-wallpaper__logo">
        <div class="title">WELCOME </div>
        <div class="desc">This application will allow you to see your pins and users with repin information.
</div>
<button></button>
      </div>
    </div>

  </div>
</template>

<script>

export default {
  name: 'dashboard',

  methods: {
 
  }
}

</script>
<style lang="scss" scoped>
  .dashboard {
    height: calc(100vh - #{$top-nav-height});
    .auth-wallpaper {
      height: 100%;
      background-color: white;
      overflow: hidden;
      display: flex;
      align-items: center;
      justify-content: center;
      &__logo {
        z-index: 2;
        width: 100%;
      }
      .auth-wallpaper__logo {
        text-align: center;
        .title {
          font-size: 64px;
          font-weight: bold;
          letter-spacing: 3px;
          color: #22C1AD;
        }
        .desc {
          font-size: 18px;
          color: grey;
        }
      }
      
    }
  }

</style>
