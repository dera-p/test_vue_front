<template>
  <div class="container">
    <h1 class="animated-title">Welcome to My Test Vue Page</h1>
    <p>This is an example of an awesome Vue.js page. Feel free to customize it according to your needs.</p>
  </div>
</template>

<script>
export default {
  name: 'App',
};
</script>

<style>
.container {
  max-width: 800px;
  margin: 0 auto;
  padding: 20px;
  background-color: #fff;
  box-shadow: 0 0 5px rgba(0, 0, 0, 0.2);
  text-align: center;
}

.animated-title {
  animation: pulse 2s infinite;
  color: #8bc34a;
}

@keyframes pulse {
  0% {
    transform: scale(1);
  }

  50% {
    transform: scale(1.2);
  }

  100% {
    transform: scale(1);
  }
}

p {
  color: #666;
  font-size: 16px;
  line-height: 1.5;
}
</style>
