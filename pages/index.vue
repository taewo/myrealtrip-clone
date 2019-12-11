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
          <div class="content-container">
            <ul class="">
              <li>
                <a href="/">
                  <span>투어&티켓</span>
                </a>
              </li>
              <li>
                <a href="/">
                  <span>항공권</span>
                </a>
              </li>
              <li>
                <a href="/">
                  <span>숙소</span>
                </a>
              </li>
              <li>
                <a href="/">
                  <span>특가여행</span>
                </a>
              </li>
              <li>
                <a href="/">
                  <img src="data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNCIgaGVpZ2h0PSIxNCIgdmlld0JveD0iMCAwIDE0IDE0Ij4KICAgIDxnIGZpbGw9Im5vbmUiIGZpbGwtcnVsZT0iZXZlbm9kZCI+CiAgICAgICAgPGNpcmNsZSBjeD0iNyIgY3k9IjciIHI9IjciIGZpbGw9IiNGQTVCNEEiLz4KICAgICAgICA8cGF0aCBmaWxsPSIjRkZGIiBmaWxsLXJ1bGU9Im5vbnplcm8iIGQ9Ik00LjUxMiA5LjVWMy44Mkg1LjhsMi4yNjQgMy41MDQuMDE2LS4wMDhWMy44Mkg5LjRWOS41SDguMDcyTDUuODQ4IDYuMDkyaC0uMDE2VjkuNXoiLz4KICAgIDwvZz4KPC9zdmc+Cg==" alt="">
                  <span>패키지</span>
                </a>
              </li>
              <li>
                <a href="/">
                  <span>여행자보험</span>
                </a>
              </li>
              <li>
                <a href="/">
                  <span>여행준비</span>
                </a>
              </li>
            </ul>
          </div>
        </div>
      </header>
      <main class="main">
        <div>
          <section class="first">
            <h2>
              어디로 떠나세요?
            </h2>
            <input type="text" placeholder="여행지나 상품을 검색해보세요!">
          </section>
        </div>

      </main>
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
$white-font: #fff;
$blue-backgroundcolor: #2b96ed;

html,
body {
  margin: 0;
}

a {
  text-decoration: none;

}
// ======= header 시작
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
    height: 50px;
    ul {
      list-style: none;
      padding: 0;
      margin: 0;
    }
    li {
      position: relative;
      display: inline-block;
      height: 50px;
      line-height: 50px;
    }
    li:hover {
      color: red;
      // border-bottom-color: $white-font;
      border-bottom: 3px solid red;
    }
    a {
      box-sizing: border-box;
      height: 50px;
      color: inherit;
      margin: 0 12px;
      span {
        margin: 0 4px;
        box-sizing: border-box;
      }
      span:first-child {
        margin-left: 0;
      }
      img {
        position: absolute;
        right: 0;
        top: 7px;
      }
    }
    a:first-child {
      margin-left: 0;
    }
    color: $white-font;
    font-size: 16px;
  }
}
// ======= header 끝

// ======= main 시작
.main {
  .first {
    background-color: $blue-backgroundcolor;
    height: 309px;
    border-top: 1px solid #1583db;
    color: $white-font;
      h2 {
      margin-top: 56px;
      margin-bottom: 16px;
    }
  }
}


// ======= main 끝



.content-container {
  margin: 0 102px;
  height: 100%;
  position: relative;
}

</style>

