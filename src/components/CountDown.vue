<template>
  <div class="count_down">
    <p class="count_text">OFFER ENDS IN</p>
    <p class="count_time">{{ countdown }}</p>
  </div>
</template>

<script setup>
import { ref, onMounted, onUnmounted } from 'vue'

const endDate = new Date('2024-11-02T23:59:59');

const countdown = ref('');

const calculateTimeLeft = () => {
  const now = new Date();
  const timeDifference = endDate - now;

  if (timeDifference <= 0) {
    countdown.value = 'Time is up!';
    return;
  }

  const days = Math.floor(timeDifference / (1000 * 60 * 60 * 24));
  const hours = Math.floor((timeDifference / (1000 * 60 * 60)) % 24);
  const minutes = Math.floor((timeDifference / 1000 / 60) % 60);

  countdown.value = `${days} days ${hours} hours ${minutes} minutes`;
};

onMounted(() => {
  calculateTimeLeft();
  const interval = setInterval(calculateTimeLeft, 60000); // Оновлюємо кожну хвилину

  onUnmounted(() => {
    clearInterval(interval); // Очищаємо інтервал при виході з компонента
  });
});
</script>

<style lang="scss" scoped>
.count_down {
    color: var(--RS-Wrong, #FF981F);
    text-align: center;
    -webkit-text-stroke-width: 1px;
    -webkit-text-stroke-color: #000;
    font-family: Zombie;
    font-size: 24px;
    font-style: normal;
    font-weight: 400;
    line-height: normal;
    text-align: center;
    padding: 24px;
    width: 200px;
    border-radius: 15px;
    border: 1px solid rgba(174, 174, 174, 0.20);
    background: linear-gradient(11deg, rgba(27, 3, 3, 0.80) -12.66%, rgba(40, 40, 40, 0.17) 101.63%);
    box-shadow: 0px 4px 4px 0px rgba(0, 0, 0, 0.31);
    backdrop-filter: blur(4px);
    position: fixed;
    top: 5px;
    left: 5px;
    z-index: 11;

    .count_text {
        color: var(--RS-Wrong, #C7332A);
        margin: 0;
    }

    .count_time {
        margin: 0;
        width: 200px;
        margin: auto;
    }
}

@media (max-width: 575.98px) {
    .count_down {
        border-radius: unset;
        width: 100%;
        top: 0;
        left: 0;
        font-size: 14px;
        padding: 10px;
    }

    .count_time {
        margin: 0;
        width: 125px;
        margin: auto;
    }
}
</style>
