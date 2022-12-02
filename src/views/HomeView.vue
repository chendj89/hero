<script setup lang="ts"></script>

<template>
  <div class="box box1">
    <div class="icon success">
      <svg
        stroke="currentColor"
        fill="currentColor"
        stroke-width="0"
        viewBox="0 0 16 16"
        height="1em"
        width="1em"
        xmlns="http://www.w3.org/2000/svg"
      >
        <path
          d="M13.485 1.431a1.473 1.473 0 0 1 2.104 2.062l-7.84 9.801a1.473 1.473 0 0 1-2.12.04L.431 8.138a1.473 1.473 0 0 1 2.084-2.083l4.111 4.112 6.82-8.69a.486.486 0 0 1 .04-.045z"
        ></path>
      </svg>
    </div>
  </div>
</template>
<style lang="scss" scoped>
.box {
  margin-left: 110px;
  margin-top: 130px;

  padding: 0 1rem;
  border-radius: 0.5rem;
  width: 20rem;
  height: 4.5rem;
  padding: 1rem;
}
.box1 {
  background: rgba(#fff, 0.3);
  backdrop-filter: blur(7px);
}

.icon {
  display: flex;
  align-items: center;
  justify-content: center;
  width: 2.5rem;
  height: 2.5rem;
  border-radius: 0.3rem;
  margin-right: 1rem;
  font-size: 1rem;
  color: white;
  background: #10b981;
}
</style>
