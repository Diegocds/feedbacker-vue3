<template>
  <div>
    <custom-header @create-account="handleAccountCreate" @login="handleLogin" />
    <contact />
    <div class="footer">
      <p>feedbacker ° 2022</p>
    </div>
  </div>
</template>
<script>
// import { onMounted } from "vue";
// import { useRouter } from "vue-router";
import CustomHeader from "./CustomHeader.vue";
import Contact from "./Contact.vue";
export default {
  components: {
    CustomHeader,
    Contact,
  },
  setup() {
    // const router = useRouter();
    // onMounted(() => {
    //   const token = window.localStorage.getItem("token");
    //   if (token) {
    //     router.push({ name: "Feedbacks" });
    //   }
    // });
    function handleLogin() {
      console.log("login");
    }
    function handleAccountCreate() {
      console.log("account create");
    }
    return {
      handleLogin,
      handleAccountCreate,
    };
  },
};
</script>
<style lang="scss" scoped>
.footer {
  display: flex;
  justify-content: center;
  align-items: center;
  width: 100%;
  height: 110px;
  background: #f4f4f4;
  p {
    font-family: "Roboto";
    font-style: normal;
    font-weight: 700;
    font-size: 16px;
    line-height: 21px;
    color: #444444;
  }
}
</style>
