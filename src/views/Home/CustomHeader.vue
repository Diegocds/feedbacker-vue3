<template>
  <header class="header">
    <div class="header__container">
      <div class="header__container__content">
        <div class="header__container__content__logo">
          <img src="../../assets/images/logo_white.png" alt="logo" />
        </div>
        <div class="header__container__content__buttons">
          <button class="header__container__content__buttons__account">
            Crie uma conta
          </button>
          <button class="header__container__content__buttons__enter">
            Entrar
          </button>
        </div>
      </div>
      <div class="header__container__text">
        <div class="header__container__text__description">
          <h1>
            Tanha um feedback. <br />
            E faça seus clientes mais <br />
            felizes.
          </h1>
          <p>
            Receba ideias, reclamações e feedbacks com um <br />
            simples widget na página.
          </p>

          <button>Crie uma conta grátis</button>
        </div>
        <div class="header__container__text__balloon">
          <img src="../../assets/images/blue_balloons.png" alt="balões" />
        </div>
      </div>
    </div>
  </header>
</template>

<script>
export default {};
</script>

<style lang="scss" scoped>
.header {
  height: 700px;
  background: #ef4983;
  &__container {
    &__content {
      display: flex;
      justify-content: space-between;
      align-items: center;
      margin: 0 160px 24px;
      padding-top: 30px;
      &__logo {
        height: 43px;
        width: 150px;
        img {
          height: 43px;
          width: 150px;
        }
      }
      &__buttons {
        &__account {
          width: 150px;
          height: 36px;
          font-family: "Roboto", sans-serif;
          background: #ef4983;
          color: #fff;
          font-size: 18px;
          font-weight: 500;
          border-radius: 23px;
          margin-top: 10px;
        }
        &__enter {
          width: 93px;
          height: 36px;
          font-family: "Roboto", sans-serif;
          background: #fff;
          color: #ef4983;
          font-size: 18px;
          font-weight: 500;
          border-radius: 23px;
          margin-top: 10px;
        }
      }
    }
    &__text {
      display: flex;
      justify-content: space-between;
      align-items: center;
      &__description {
        margin-left: 160px;
        margin-bottom: 30px;
        h1 {
          font-family: "Roboto", sans-serif;
          font-size: 42px;
          font-weight: 700;
          line-height: 56px;
          color: #fff;
          margin-bottom: 10px;
        }
        p {
          font-family: "Roboto", sans-serif;
          font-size: 22px;
          font-weight: 400;
          line-height: 28px;
          color: #fff;
          margin-bottom: 30px;
        }
        button {
          width: 220px;
          height: 38px;
          font-family: "Roboto", sans-serif;
          background: #fff;
          color: #ef4983;
          font-size: 18px;
          font-weight: 500;
          border-radius: 23px;
          margin-top: 10px;
        }
      }
      &__balloon {
        height: 628px;
        width: 600px;
        margin-right: 100px;
      }
    }
  }
}
</style>
