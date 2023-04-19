<template>
  <div class="header">
    <div class="logo">
      <img src="imgs/logo.png" />
    </div>
    <div class="actions">
      <button>
        <img src="imgs/icons/wallet.svg" />
        <span>POOL</span>
      </button>

      <button>
        <img src="imgs/icons/wallet.svg" />
        <span>SWAP</span>
      </button>

      <button>
        <img src="imgs/icons/wallet.svg" />
        <span>123456 DICE</span>
      </button>

      <button class="wallet">Connect Wallet</button>
    </div>
  </div>
</template>

<script>
export default {
  name: "Header",
};
</script>

<style lang="scss">
.header {
  height: 60px;
  display: flex;
  box-sizing: border-box;
  justify-content: space-between;
  position: absolute;
  top: 0;
  width: 100%;
  z-index: 100;
  align-items: center;
  padding: 0 20px;

  .logo {
    display: flex;
    align-items: center;

    img {
      height: 36px;
    }
  }

  .actions {
    display: flex;
    align-items: center;

    button {
      margin: 0 5px;
      border: none;
      border-radius: 20px;
      border: 5px solid #120f1f;
      background: #2a2735;
      display: flex;
      align-items: center;
      font-size: 14px;
      padding: 3px 10px;
      color: #fff;

      img {
        margin-right: 10px;
      }

      span {
        line-height: -1;
      }
    }

    .wallet {
      margin: 0 5px;
      border: none;
      border-radius: 20px;
      background: #3064ad;
      display: flex;
      align-items: center;
      font-size: 14px;
      padding: 8px 10px;
      color: #fff;
    }
  }
}
</style>
