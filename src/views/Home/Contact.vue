<template>
  <div class="container">
    <h1>Alguma dúvida ?</h1>
    <p>Quer saber melhor como funciona e quais são os preços?</p>
    <div class="container__link">
      <a href="mailto:"> Nos mande um e-mail!</a>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style lang="scss" scoped>
.container {
  text-align: center;
  margin: 55px 0 75px;
  h1 {
    font-family: "Roboto", sans-serif;
    color: #444444;
    font-weight: 700;
    font-size: 44px;
    line-height: 56px;
  }
  p {
    font-family: "Roboto";
    color: #444444;
    font-weight: 400;
    font-size: 22px;
    line-height: 28px;
  }
  &__link {
    width: 220px;
    height: 38px;
    background: #ef4983;
    border-radius: 23px;
    margin: 30px auto 0;
    padding-top: 5px;
    a {
      font-family: "Roboto", sans-serif;
      color: #fff;
      font-size: 16px;
      font-weight: 500;
    }
  }
}
</style>
