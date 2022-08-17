<script setup lang="ts">
const { currentUser, login } = useAuth();

const userLogin = async () => {
  await login();
};
</script>

<template>
  <div>
    <button @click="userLogin">ログイン</button>
  </div>
</template>
