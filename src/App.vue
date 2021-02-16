<template>
  <div id="app">
    <div id="nav">
      <div class="tabs">
        <router-link to="/" class="signIn">تسجيل الدخول </router-link>
        <router-link to="/" class="signUp">إنشاء حساب</router-link>
      </div>
      <img :src="logo" alt="" />
    </div>
    <router-view />
  </div>
</template>

<script>
export default {
  data() {
    return {
      logo: require("./views/svgs/logo.svg")
    };
  }
};
</script>
<style lang="scss">
html,
body {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
#app {
  font-family: "Cairo", sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  width: 100%;
  background-color: rgb(243, 243, 243);
  color: #012e43;
  box-sizing: border-box;
  h1,
  h2,
  h3,
  h4,
  h5,
  h5 {
    margin: 0;
  }
}

#nav {
  padding: 30px 6rem;
  display: flex;
  flex-wrap: wrap;
  justify-content: space-between;
  align-items: center;
  .tabs {
    display: flex;
    flex-direction: row-reverse;
    flex-wrap: wrap;
    gap: 5px;
    align-items: center;
    .signIn {
      color: white;
      background-color: #fea403;
      padding: 5px 15px;
      border-radius: 2rem;
      margin: 0 20px;
    }
    .signUp {
      color: black;
      margin: 0 20px;
    }
  }

  a {
    text-decoration: none;
    font-weight: 600;
  }
}
@media screen and (min-width: 320px) and (max-width: 567px) {
  #nav {
    padding: 1rem;
    a {
      margin: 0 !important;
    }
  }
}
</style>
