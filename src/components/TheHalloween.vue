<template>
  <div class="main">
    <CountDown />
    <div class="title mobile">
      <h1>Ball Hard’s Caskets - Halloween PROMO</h1>
    </div>
    <div class="container">
      <section class="promo">
        <div class="title desktop">
          <h1>Ball Hard’s Caskets - Halloween PROMO</h1>
          <img class="treat_cauldron" src="@/assets/Box.png" alt="Box" />
          <img
            class="spider_back"
            src="@/assets/right_spider.gif"
            alt="spider_back"
          />
        </div>
        <p class="title_description">
          For Every <span class="green_text">$100</span> you invest in your
          account, you receive one Ball Hard's Casket filled with random loot!
        </p>
        <div class="gif_object">
          <img class="hay_bale" src="@/assets/Hay_bale.png" alt="hay bale" />
          <img
            class="cauldron"
            src="@/assets/casket_rotated.gif"
            alt="animated_casket"
          />
          <img
            class="hay_bale_small"
            src="@/assets/Hay_bale_small.png"
            alt="hey"
          />
          <img
            class="snoop_dog_dance"
            src="@/assets/Snoop_Dog_Dance.gif"
            alt="Snoop_Dog_Dance"
          />
          <img
            class="jack_lantern"
            src="@/assets/Jack_lantern.png"
            alt="Jack_lantern"
          />
        </div>
        <button @click.prevent="redirectUrl">
          <img
            class="red_button"
            src="@/assets/red_button.png"
            alt="red_button"
          />
          <span class="button_text">Grab Ball Hard's Caskets</span>
        </button>
        <div class="spider_block">
          <img
            class="spider_back"
            src="@/assets/left_spider.gif"
            alt="spider_back"
          />
        </div>
      </section>

      <section class="web">
        <div class="wrapper_web">
          <h3>What’s Inside The Casket?</h3>
          <div class="wrapper_items">
            <div class="item">
              <img
                class="item_img"
                src="@/assets/Bow_of_faerdhinen.png"
                alt="Bow_of_faerdhinen"
              />
              <img
                class="item_background"
                src="@/assets/Ellipse 1.svg"
                alt="ellipse"
              />
              <h4>Items</h4>
            </div>

            <div class="item">
              <img
                class="item_img"
                src="@/assets/Marcus_scimitar_final.png"
                alt="Marcus_scimitar_final"
              />
              <img
                class="item_background"
                src="@/assets/Ellipse 1.svg"
                alt="ellipse"
              />
              <h4>coaching</h4>
            </div>

            <div class="item">
              <img class="item_img" src="@/assets/Group.svg" alt="Group" />
              <img
                class="item_background"
                src="@/assets/Ellipse 1.svg"
                alt="ellipse"
              />
              <h4>Boosting Vouchers</h4>
            </div>

            <div class="item">
              <img class="item_img" src="@/assets/money.gif" alt="money" />
              <img
                class="item_background"
                src="@/assets/Ellipse 1.svg"
                alt="ellipse"
              />
              <h4>gold</h4>
            </div>

            <div class="item">
              <img
                class="item_img"
                src="@/assets/Dragon_scimitar_detail.png"
                alt="Dragon_scimitar_detail"
              />
              <img
                class="item_background"
                src="@/assets/Ellipse 1.svg"
                alt="ellipse"
              />
              <h4>Real-Life Size Physical Dragon Scimitar</h4>
            </div>
          </div>
          <img
            class="spider_back"
            src="@/assets/right_spider.gif"
            alt="spider_back"
          />
        </div>
        <button @click.prevent="redirectUrl">
          <img
            class="red_button"
            src="@/assets/red_button.png"
            alt="red_button"
          />
          <span class="button_text">Grab Ball Hard's Caskets</span>
        </button>
        <div class="devider"></div>
      </section>
      <section class="logo">
        <svg
          xmlns="http://www.w3.org/2000/svg"
          width="80"
          height="78"
          viewBox="0 0 80 78"
          fill="none"
        >
          <path
            d="M40.0397 77.3711C61.8768 77.3711 79.5794 60.1341 79.5794 38.8711C79.5794 17.6081 61.8768 0.371094 40.0397 0.371094C18.2025 0.371094 0.5 17.6081 0.5 38.8711C0.5 60.1341 18.2025 77.3711 40.0397 77.3711Z"
            fill="url(#paint0_linear_1_143)"
          />
          <path
            fill-rule="evenodd"
            clip-rule="evenodd"
            d="M13.1398 18.0431C13.1398 18.0431 16.9945 18.4986 17.1911 18.5166C18.2724 18.6157 19.5542 19.7595 19.5806 21.1534C19.6128 22.8494 19.6366 55.94 19.6218 55.9127C19.6218 55.9127 19.4816 57.7872 18.3254 58.7524C17.059 59.8088 12.9777 59.8571 12.9777 59.8571V61.9083H30.9649C30.9649 61.9083 43.3806 61.3431 47.3307 56.5431C51.5959 51.3634 51.2953 47.1756 50.3155 44.823C48.8573 41.3195 45.4642 39.2217 44.9 39.0289C44.3032 38.8252 53.8127 39.0289 53.8127 39.0289L53.6506 56.2278C53.6506 56.2278 53.2089 58.7057 52.03 59.0675C50.8511 59.4293 47.0065 59.8566 47.0065 59.8566V61.7499H67.1005V59.8566C67.1005 59.8566 62.9189 59.8839 61.7529 58.5943C61.1544 57.9245 60.7613 57.1044 60.6185 56.2275V21.3569C60.6185 21.3569 60.8148 19.4349 62.0768 18.8323C63.5484 18.1292 67.1003 17.8856 67.1003 17.8856L66.9382 15.8344H47.4939V18.0434C47.4939 18.0434 51.7255 17.9424 52.6795 19.1479C53.4027 20.0502 53.8012 21.159 53.8138 22.3035V36.0314L40.8498 36.1892C40.8613 36.1185 47.117 33.7236 47.8402 27.6326C48.2474 24.2007 47.0982 20.0386 43.015 17.8334C39.3678 15.8639 33.7512 15.8424 30.6407 15.8347C27.8884 15.8282 13.3605 15.8391 13.1398 15.8347V18.0431ZM26.2656 36.0314H33.5566C35.7476 35.5751 37.7663 34.5375 39.3894 33.0336C40.0935 32.3782 41.234 28.8354 40.6858 25.6175C40.2651 23.1451 39.0226 21.0961 37.607 20.0951C36.2181 19.1121 36.0801 18.8077 33.3937 18.3593C31.9197 18.1136 29.0852 18.761 27.5608 20.2527C26.7886 21.0082 26.4406 23.2655 26.4265 24.0396C26.4148 24.7413 26.2656 36.0314 26.2656 36.0314ZM26.2656 39.0295V54.6504C26.2656 54.6504 26.5533 56.7482 27.8861 57.806C29.9414 59.4375 33.3824 59.7348 36.4747 58.7527C39.5669 57.7705 41.0585 56.3354 42.3075 54.0191C43.716 51.409 44.1782 46.8018 42.1454 43.6052C40.8344 41.5434 38.464 40.2096 37.1219 39.6605C36.3996 39.3483 35.636 39.1359 34.8533 39.0295H26.2656Z"
            fill="url(#paint1_linear_1_143)"
          />
          <defs>
            <linearGradient
              id="paint0_linear_1_143"
              x1="40.0397"
              y1="77.3711"
              x2="40.0397"
              y2="0.371094"
              gradientUnits="userSpaceOnUse"
            >
              <stop stop-color="#E09F02" />
              <stop offset="1" stop-color="#FDD966" />
            </linearGradient>
            <linearGradient
              id="paint1_linear_1_143"
              x1="40.0397"
              y1="61.9091"
              x2="40.0397"
              y2="15.832"
              gradientUnits="userSpaceOnUse"
            >
              <stop stop-color="#1D3934" />
              <stop offset="1" stop-color="#142927" />
            </linearGradient>
          </defs>
        </svg>
        <svg
          xmlns="http://www.w3.org/2000/svg"
          width="386"
          height="36"
          viewBox="0 0 386 36"
          fill="none"
        >
          <path
            fill-rule="evenodd"
            clip-rule="evenodd"
            d="M17.5096 17.5609C20.4358 16.7418 24.5028 14.9124 24.5028 10.2391C24.5028 7.97527 23.4116 5.80752 21.6262 4.65143C19.9893 3.54367 17.7577 2.96563 13.889 2.96563H0.596958V4.4106C4.6631 4.69949 4.86248 4.98865 4.86248 9.08303V28.688C4.86248 32.7837 4.56467 33.0713 0.200439 33.4085V34.8054H11.6571C15.6742 34.8054 19.1461 34.2274 21.7243 32.8304C24.7495 31.2407 26.535 28.688 26.535 25.4125C26.535 20.5473 22.6169 18.3798 17.5084 17.6579V17.5609H17.5096ZM9.37589 17.079V7.54221C9.37589 5.95252 9.57415 5.4228 10.0209 5.13364C10.5169 4.84475 11.6081 4.60392 12.8478 4.60392C17.5589 4.60392 19.5435 7.44582 19.5435 10.8658C19.5435 14.9601 17.262 17.0796 11.7071 17.0796H9.37617L9.37589 17.079ZM9.37589 18.7173H11.6078C17.8071 18.7173 21.3287 20.9814 21.3287 25.8947C21.3287 31.0488 17.6585 33.0238 13.6411 33.0718C10.3678 33.0718 9.37589 32.1565 9.37589 28.5922V18.7173ZM59.3678 34.8059V33.409C56.0448 33.0718 55.3505 32.5899 53.7635 28.3513C50.4902 19.7776 47.1175 10.7694 43.8926 2.24368L42.2064 2.67728L31.6423 28.3033C29.8073 32.5901 29.1129 32.9276 25.8395 33.4093V34.8062H37.0483V33.4093C33.1303 33.024 32.7335 32.494 33.8742 29.4594C34.5192 27.4844 35.2133 25.5097 36.0054 23.2456H46.9167C48.0078 26.1839 48.9501 28.7369 49.5948 30.6638C50.2891 32.5424 49.8429 32.9757 46.6192 33.4093V34.8062H59.3678V34.8059ZM46.1262 21.1739H36.9003C38.3879 17.1759 39.9255 12.9371 41.6114 8.84275H41.7104L46.1262 21.1739ZM83.2234 26.7627C82.3802 29.0268 81.4379 30.6163 80.5451 31.5796C79.355 32.784 77.6189 33.0729 74.8912 33.0729C72.7586 33.0729 71.0724 32.9765 70.0802 32.4468C69.138 31.9651 68.8901 31.0015 68.8901 28.4005V9.13191C68.8901 4.89281 69.3366 4.65198 73.4033 4.41115V2.96617H59.8636V4.41115C63.9799 4.70004 64.3271 4.94114 64.3271 9.13191V28.5438C64.3271 32.7346 63.9306 33.0718 59.665 33.409V34.8059H82.828C83.3734 33.3126 84.4149 28.5922 84.7127 27.0025L83.2234 26.7627ZM108.219 26.7627C107.375 29.0268 106.433 30.6163 105.541 31.5796C104.35 32.784 102.614 33.0729 99.8864 33.0729C97.7538 33.0729 96.0676 32.9765 95.0758 32.4468C94.1333 31.9651 93.8854 31.0015 93.8854 28.4005V9.13191C93.8854 4.89281 94.3318 4.65198 98.3985 4.41115V2.96617H84.8583V4.41115C88.9749 4.70004 89.322 4.94114 89.322 9.13191V28.5438C89.322 32.7346 88.9252 33.0718 84.66 33.409V34.8059H107.821C108.367 33.3126 109.408 28.5922 109.706 27.0025L108.219 26.7627ZM154.54 2.96617H140.999V4.41115C144.967 4.70004 145.413 4.9892 145.413 9.08358V16.9351H128.105V9.08358C128.105 4.9892 128.551 4.70031 132.469 4.41115V2.96617H118.979V4.41115C123.145 4.70004 123.592 4.9892 123.592 9.08358V28.6885C123.592 32.831 123.145 33.0718 119.128 33.409V34.8059H132.718V33.409C128.551 33.0718 128.105 32.7829 128.105 28.6885V19.0065H145.414V28.6885C145.414 32.831 144.968 33.0718 140.653 33.409V34.8059H154.54V33.409C150.374 33.0718 149.977 32.831 149.977 28.6885V9.08358C149.977 4.9892 150.374 4.70031 154.54 4.41115V2.96617ZM186.579 34.8059V33.409C183.256 33.0718 182.562 32.5899 180.974 28.3513C177.701 19.7776 174.328 10.7694 171.104 2.24368L169.417 2.67728L158.853 28.3033C157.018 32.5901 156.324 32.9276 153.05 33.4093V34.8062H164.259V33.4093C160.341 33.024 159.944 32.494 161.085 29.4594C161.73 27.4844 162.424 25.5097 163.218 23.2456H174.129C175.22 26.1839 176.162 28.7369 176.807 30.6638C177.501 32.5424 177.055 32.9757 173.831 33.4093V34.8062H186.579V34.8059ZM173.337 21.1739H164.111C165.599 17.1759 167.136 12.9371 168.822 8.84275H168.921L173.337 21.1739ZM217.378 33.939C216.237 33.6018 215.095 33.0238 213.758 31.6268C212.518 30.4227 211.525 29.0738 209.641 26.4727C208.152 24.305 206.021 21.0295 205.126 19.3917C208.847 17.8504 211.624 15.296 211.624 11.1066C211.624 8.12025 210.286 5.90446 208.202 4.65198C206.268 3.3995 203.836 2.96617 199.969 2.96617H187.173V4.41115C191.141 4.70004 191.537 4.94114 191.537 9.08358V28.6402C191.537 32.7346 191.091 33.0718 186.975 33.409V34.8059H200.564V33.409C196.447 33.0718 196.001 32.7346 196.001 28.6402V20.9331H197.538C200.118 20.9331 201.01 21.5112 201.904 22.9081C203.39 25.2683 205.177 28.303 206.963 30.7116C209.243 33.8907 211.377 34.9504 215.345 35.1432C215.939 35.1912 216.534 35.1912 217.179 35.1912L217.378 33.939ZM196.001 19.2954V7.25387C196.001 5.90528 196.15 5.37529 196.548 5.13446C196.943 4.84557 197.835 4.6528 199.274 4.6528C203.043 4.6528 206.615 6.57971 206.615 11.8302C206.615 14.5276 205.822 16.4062 203.887 17.8993C202.597 18.9095 200.911 19.2962 198.332 19.2962H196.001V19.2954ZM216.534 2.96699V4.41197C220.451 4.70085 220.897 4.94196 220.897 9.13272V28.641C220.897 32.8318 220.451 33.121 216.037 33.4579V34.8068H228.438C234.686 34.8068 239.843 33.5543 243.662 30.7604C247.579 27.9185 250.011 23.5353 250.011 17.7068C250.011 13.0824 248.177 9.518 245.647 7.20581C242.473 4.26753 237.661 2.96699 231.164 2.96699H216.534ZM225.46 8.12107C225.46 6.19416 225.611 5.61612 226.105 5.27917C226.652 4.94196 227.941 4.65307 230.174 4.65307C233.645 4.65307 236.621 5.32751 238.9 6.77248C242.77 9.08467 244.753 13.3235 244.753 18.4295C244.753 26.1841 240.291 32.9765 230.866 32.9765C227.148 32.9765 225.46 32.0615 225.46 28.3041V8.12026V8.12107ZM255.961 0.0287018L251.845 1.37757C252.044 2.052 252.885 7.20609 253.432 11.8785L254.921 11.2524C255.367 8.1694 256.16 1.47395 256.259 0.269806L255.961 0.0287018ZM277.038 10.1924C276.643 7.06137 276.345 5.13446 276.146 3.40059C274.262 2.82255 272.08 2.2445 269.649 2.2445C263.053 2.2445 259.085 6.24249 259.085 11.0594C259.085 16.5026 264.046 18.9592 267.518 20.6931C271.385 22.6681 274.063 24.4022 274.063 27.9666C274.063 31.4832 271.881 33.7951 268.112 33.7951C262.854 33.7951 260.473 28.7374 259.68 25.6547L258.194 26.04C258.491 28.4485 259.183 32.7354 259.531 33.7946C260.358 34.1935 261.222 34.5161 262.111 34.7582C263.729 35.2677 265.419 35.5273 267.119 35.5276C273.965 35.5276 278.527 31.3852 278.527 26.1828C278.527 20.7878 273.864 18.4757 269.699 16.4046C265.63 14.4296 263.252 12.7435 263.252 9.27553C263.252 6.57807 265.036 3.97673 268.855 3.97673C273.219 3.97673 274.657 7.44446 275.552 10.5277L277.038 10.1924ZM289.239 2.96699V4.41197C293.157 4.70085 293.603 4.94196 293.603 9.13272V28.641C293.603 32.8318 293.157 33.121 288.743 33.4579V34.8068H301.14C307.391 34.8068 312.548 33.5543 316.367 30.7604C320.285 27.9185 322.716 23.5353 322.716 17.7068C322.716 13.0824 320.879 9.518 318.35 7.20581C315.176 4.26753 310.366 2.96699 303.869 2.96699H289.239ZM298.165 8.12107C298.165 6.19416 298.314 5.61612 298.81 5.27917C299.357 4.94196 300.644 4.65307 302.876 4.65307C306.348 4.65307 309.326 5.32751 311.606 6.77248C315.476 9.08467 317.458 13.3235 317.458 18.4295C317.458 26.1841 312.994 32.9765 303.572 32.9765C299.85 32.9765 298.165 32.0615 298.165 28.3041V8.12026V8.12107ZM348.504 26.8108C347.887 28.4691 347.019 30.0278 345.927 31.4349C344.785 32.6874 343.296 33.0732 339.527 33.0732C337.099 33.0732 335.313 33.0251 334.32 32.4471C333.378 31.869 333.081 30.8088 333.081 28.4971V19.3437H337.842C342.256 19.3437 342.604 19.6326 343.296 23.1489H344.785V13.7079H343.296C342.651 16.9845 342.354 17.3687 337.792 17.3687H333.081V6.28973C333.081 4.84475 333.179 4.74837 334.816 4.74837H338.585C342.206 4.74837 343.546 5.08558 344.289 6.09723C344.985 7.20499 345.478 8.31276 345.974 10.2877L347.514 10.0966C347.315 7.54357 347.065 4.21974 347.018 2.96754H324.202V4.41251C328.12 4.7014 328.518 4.89417 328.518 9.27771V28.6416C328.518 32.6396 328.12 33.0251 323.459 33.4104V34.8073H348.257C348.703 33.2659 349.696 28.691 349.993 27.0038L348.504 26.8108ZM385.503 2.96699H373.403V4.41197C376.972 4.60474 378.212 5.23112 378.461 7.44664C378.61 8.84356 378.806 11.0594 378.806 15.5873V27.3405H378.658L357.332 2.96699H349.595V4.41197C351.975 4.60474 353.066 4.99001 354.157 6.19416C355.052 7.35026 355.15 7.63914 355.15 11.2038V21.8478C355.15 26.3278 355.001 28.6397 354.853 30.2305C354.555 32.5907 353.265 33.2651 350.388 33.4096V34.8065H362.491V33.4096C358.969 33.2168 357.878 32.5426 357.581 30.086C357.432 28.6408 357.284 26.3288 357.284 21.8489V9.70968H357.382L379.303 35.2876H380.94V15.5865C380.94 11.0585 381.089 8.8422 381.238 7.34944C381.484 5.13364 382.676 4.55559 385.503 4.41115V2.96617V2.96699Z"
            fill="#FEFEFE"
          />
        </svg>
      </section>
    </div>
  </div>
</template>

<script setup>
import CountDown from "./CountDown.vue"
const redirectUrl = () => {
  window.location.href = "https://pimpmybuild.ballhardsden.com/";
};
</script>

<style lang="scss">
@import url("https://fonts.cdnfonts.com/css/zombie");
.spider_block {
  position: absolute;
  z-index: 10;
  top: 50%;
}

h1 {
  color: var(--RS-Wrong, #c7332a);
  text-align: center;
  -webkit-text-stroke-width: 1px;
  -webkit-text-stroke-color: #000;
  font-family: Zombie;
  font-size: 64px;
  font-style: normal;
  font-weight: 400;
  line-height: normal;
  margin: 0;
}

.logo {
  display: flex;
  flex-direction: row;
  gap: 16px;
  align-items: center;
  justify-content: center;
}
.devider {
  background: rgba(174, 174, 174, 0.2);
  width: 100%;
  height: 1px;
  margin-top: 32px;
}

.promo {
  text-align: center;
  width: 100%;
  position: relative;
  display: flex;
  flex-direction: column;
  gap: 60px;
}

button {
  background-color: transparent;
  border: none;
  cursor: pointer;
  transition: transform 0.3s ease;
  position: relative;
  max-width: 462px;
  margin: auto;
  
  &:hover {
    transform: scale(1.2);
  }

  img {
    width: 100%;
  }

  .button_text {
    position: absolute;
    left: 50%;
    top: 50%;
    transform: translate(-50%, -50%);
    color: #fff;
    text-align: center;
    -webkit-text-stroke-width: 1px;
    -webkit-text-stroke-color: #000;
    font-family: Zombie;
    font-size: 28px;
    font-style: normal;
    font-weight: 400;
    line-height: normal;
    white-space: nowrap;
  }
}

.gif_object {
  width: 443px;
  height: 348px;
  position: relative;
  margin: 0 auto;

  img {
    position: absolute;
  }

  .hay_bale {
    bottom: 30px;
    left: 0;
    z-index: 3;
  }
  .cauldron {
    height: 182px;
    left: 88px;
    bottom: -10px;
    z-index: 4;
  }
  .hay_bale_small {
    right: 60px;
    bottom: 30px;
    z-index: 2;
  }
  .snoop_dog_dance {
    bottom: 30px;
    height: 310px;
    right: 40px;
  }

  .jack_lantern {
    bottom: 130px;
    height: 75px;
    right: 70px;
    z-index: 5;
  }
}

html {
  overflow-x: hidden;
  width: 100%;
}

body {
  background-image: url("@/assets/Halloween_event.webp");
  background-size: cover;
  background-attachment: fixed;
  background-position: center -35px;
  margin: 0;
  padding: 0 15px;
  font-family: Zombie;
  color: #f5f5f5;
  overflow-x: hidden;
}

.container {
  display: flex;
  max-width: 1120px;
  padding: 80px 40px;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  gap: 80px;
  flex-shrink: 0;
  border-radius: 15px;
  margin: 40px auto;
  border: 1px solid rgba(174, 174, 174, 0.2);
  background: linear-gradient(
    11deg,
    rgba(27, 3, 3, 0.8) -12.66%,
    rgba(40, 40, 40, 0.17) 101.63%
  );
  box-shadow: 0px 4px 4px 0px rgba(0, 0, 0, 0.31);
  backdrop-filter: blur(4px);
}

.title {
  margin: 0 15px;
  border-radius: 15px;
  background: #bdad6b;
  background-image: url("@/assets/Jack_lantern_mask_detail.png");
  background-size: contain;
  background-repeat: no-repeat;
  background-position: left;
  display: flex;
  gap: 30px;
  justify-content: space-around;
  padding: 70px 0;
  margin-bottom: 20px;
  position: relative;
  text-align: center;

  h1 {
    width: 67%;
  }

  &.mobile {
    padding: 32px 10px;
    background-image: url("@/assets/Jack_lantern_mask_detail_blur.png");
    margin-top: 48px;
    margin-bottom: 10px;
    margin-left: 0;
    margin-right: 0;
    h1 {
      font-size: 32px;
      margin: auto;
    }
  }

  .spider_back {
    position: absolute;
    top: -63.5px;
    right: -45px;
  }

  .spider_hat {
    position: absolute;
    top: -15px;
    right: -15px;
  }

  .treat_cauldron {
    height: 126px;
    position: absolute;
    top: 50%;
    transform: translateY(-50%);
    right: 25px;
  }
}
.title_description {
  margin: 0 auto;
  width: 80%;
  text-align: center;
  -webkit-text-stroke-width: 1px;
  -webkit-text-stroke-color: #000;
  font-family: Zombie;
  font-size: 40px;
  font-style: normal;
  font-weight: 400;
  line-height: normal;
  .green_text {
    color: #26eb22;
    font-family: Zombie;
    font-size: 40px;
    font-style: normal;
    font-weight: 400;
    line-height: normal;
  }
}

.web {
  width: 85%;
  margin: 0 auto;
  text-align: center;
}
.wrapper_web {
  padding: 24px;
  border-radius: 8px;
  border: 1px solid #5b5345;
  background: #40382e;
  background-image: url("@/assets/bghal.svg");
  background-repeat: no-repeat;
  background-size: cover;
  background-position: center;
  box-shadow: 0px 0px 0px 1px #383023;
  margin-bottom: 80px;
  position: relative;

  .spider_hat {
    position: absolute;
    top: -15px;
    right: -15px;
  }

  .spider_back {
    position: absolute;
    top: -63.5px;
    right: -45px;
  }

  .wrapper_items {
    display: flex;
    flex-wrap: wrap;
    gap: 16px;
    justify-content: center;

    .item {
      width: 300px;
      height: 240px;
      position: relative;
      text-align: center;

      .item_img {
        margin: 0 auto;
        display: block;
        position: relative;
        z-index: 1;
        margin-top: 50px;
      }

      .item_background {
        position: absolute;
        top: -10px;
        left: 49%;
        transform: translateX(-50%);
        z-index: 0;
      }

      h4 {
        position: absolute;
        bottom: 0;
        left: 50%;
        transform: translateX(-50%);
        color: var(--Orange, #ff981f);
        text-align: center;
        -webkit-text-stroke-width: 0.800000011920929px;
        -webkit-text-stroke-color: #000;
        font-family: Zombie;
        font-size: 20px;
        font-style: normal;
        font-weight: 400;
        line-height: normal;
        letter-spacing: 1px;
        width: 200px;
      }
      &:nth-child(1) {
        .item_img {
          margin: 0 auto;
          display: block;
          position: relative;
          z-index: 1;
          margin-top: 50px;
          top: -35px;
          left: 5px;
        }
      }

      &:nth-child(2) {
        .item_img {
          height: 125px;
          position: absolute;
          top: -40px;
          left: 48%;
          transform: translateX(-50%);
        }
      }

      &:nth-child(3) {
        .item_img {
          height: 160px;
          position: absolute;
          top: -40px;
          left: 50%;
          transform: translateX(-50%);
        }
      }

      &:nth-child(4) {
        .item_img {
          height: 108px;
          position: absolute;
          top: -5px;
          left: 50%;
          transform: translateX(-50%);
        }
        &::after {
          content: "750m";
          position: absolute;
          top: 40px;
          left: 50%;
          transform: translateX(-50%);
          color: #26eb22;
          text-align: center;
          -webkit-text-stroke-width: 0.800000011920929px;
          -webkit-text-stroke-color: #000;
          font-family: Zombie;
          font-size: 16px;
          font-style: normal;
          font-weight: 400;
          line-height: normal;
          letter-spacing: 0.8px;
        }
      }

      &:nth-child(5) {
        .item_img {
          height: 148px;
          position: absolute;
          top: -35px;
          left: 47%;
          transform: translateX(-50%);
        }

        h4 {
          margin-bottom: 0;
        }
      }
    }
  }
}

h3 {
  text-align: center;
  -webkit-text-stroke-width: 0.800000011920929px;
  -webkit-text-stroke-color: #000;
  font-family: Zombie;
  font-size: 32px;
  font-style: normal;
  font-weight: 400;
  line-height: normal;
  letter-spacing: 1.6px;
  background: var(
    --BH-Gradient,
    linear-gradient(180deg, #fcd763 0%, #e1a106 100%)
  );
  background-clip: text;
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
  margin: 0;
}

.title.mobile {
  display: none;
}
.title.desktop {
  display: flex;
}

@media (max-width: 575.98px) {
  button {
    transition: transform 0.6s ease;
    &:hover {
      transform: scale(1.1);
    }
  }
  .title_description {
    width: 100%;
  }
  .title h1 {
    width: 100%;
  }
  .title_description {
    font-size: 24px;
    .green_text {
      font-size: 24px;
    }
  }
  .title.mobile {
    display: block;
  }
  .title.desktop {
    display: none;
  }
  .container {
    padding: 24px;
    margin-top: 10px;
    gap: 60px;
  }
  .web {
    width: 100%;
  }
  .logo {
    width: 100%;
  }
  .gif_object {
    width: 270px;
    height: 200px;
  }
  .gif_object .hay_bale {
    bottom: 30px;
    left: 42px;
    z-index: 3;
    height: 130px;
  }
  .gif_object .cauldron {
    left: 50%;
    transform: translateX(-50%);
    bottom: 0;
    z-index: 4;
    height: 60%;
  }
  .gif_object .hay_bale_small {
    right: 45px;
    bottom: 30px;
    z-index: 2;
    width: 100px;
  }
  .gif_object .snoop_dog_dance {
    bottom: 30px;
    height: 190px;
    right: 20px;
  }

  .gif_object .jack_lantern {
    bottom: 91px;
    height: 45px;
    right: 40px;
    z-index: 5;
  }
  button {
    width: 100%;
    .button_text {
      width: 100%;
      font-size: 20px;
    }
  }
  .spider_block {
    position: absolute;
    z-index: 10;
    top: 25%;
    left: -55px;
  }

  h3 {
    font-size: 20px;
  }

  .wrapper_web {
    margin-bottom: 60px;
  }

  .devider {
    margin-top: 60px;
  }
}

@media (max-width: 360px) {
  button .button_text {
      font-size: 18px;
  }
}

@media (min-width: 576px) and (max-width: 767.98px) {
  .container {
    padding: 24px;
  }
  .web {
    width: 100%;
  }
  .title {
    align-items: center;

    h1 {
      font-size: 26px;
    }
  }

  h3 {
    font-size: 20px;
  }
  .title {
    padding: 40px 0;
    .treat_cauldron {
      height: 65px;
    }
  }
}

/* Medium devices (tablets, 768px and up) */
@media (min-width: 768px) and (max-width: 991.98px) {
  .title {
    align-items: center;

    h1 {
      font-size: 36px;
    }
  }
  .title {
    padding: 50px 0;
    .treat_cauldron {
      height: 85px;
    }
  }
}

/* Large devices (desktops, 992px and up) */
@media (min-width: 992px) and (max-width: 1199.98px) {
  .title {
    h1 {
      font-size: 48px;
    }
  }
}
</style>
import { h } from 'vue';
