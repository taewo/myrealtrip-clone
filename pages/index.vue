<template>
  <div>
    <div>
      <header class="header">
        <div class="header__top">
          <div class="content-container">
            <div class="header__top__left">
              <a href="/">
                <img
                  src="https://www.myrealtrip.com/webpack/5e63007c40ef9effbda3d797ea314a0e.png"
                  alt="logo"
                  class="home-logo"
                >
              </a>
            </div>
            <div class="header__top__right">
              <div class="header__top__right__container">
                <div class="menu partner">
                  <a href="/about/becomeguide">파트너등록하기</a>
                </div>
                <div class="menu login">
                  <a href="/users/sign_in">로그인</a>
                </div>
                <div class="menu signup">
                  <a href="/users/sign_up">회원가입</a>
                </div>
              </div>
            </div>
          </div>
        </div>
        <div class="header__bottom">
          <div class="content-container">1</div>
        </div>
      </header>
    </div>
    <main>
      <h1>main</h1>
    </main>
  </div>
</template>

<script>
export default {
  components: {}
};
</script>

<style lang='scss'>
html,
body {
  margin: 0;
}

a {
  text-decoration: none;
}

.header {
  background-color: #2b96ed;
  width: 100%;
  height: 123px;
  &__top {
    height: 73px;
    .home-logo {
      width: 128px;
      height: 28px;
    }
    &__left {
      width: 13%;
      float: left;
      margin-top: 21px;
    }
    &__right {
      display: inline-block;
      width: 86%;
      font-size: 15px;
      .menu {
        float: left;
        margin-top: 21px;
        margin-right: 8px;
        &.partner {
          padding: 6px 12px;
        }
        &.login {
          padding: 6px 12px;
        }
        &.signup {
          padding: 6px 32px;
          margin-left: 12px;
          border: 1px solid #fff;
        }
      }
      &__container {
        float: right;
        a {
          color: white;
        }
      }
    }
  }

  &__bottom {
    height: 53px;
  }
}

.content-container {
  margin: 0 102px;
  height: 100%;
  // border: 1px solid red;
  position: relative;
}
</style>

