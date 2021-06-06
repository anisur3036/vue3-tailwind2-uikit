<template>
  <div class="bg-gray-200 rounded-md p-4">
    <h3 class="text-2xl">Your Password</h3>
    <div class="flex items-center">
      <label for="password">Password: </label>
      <input
        class="px-2 py-1 placeholder-blueGray-300 text-blueGray-600 relative bg-white bg-white rounded text-sm border-0 shadow outline-none focus:outline-none focus:ring"
        id="password"
        :type="showPassword ? 'text' : 'password'"
        placeholder="Your password"
        v-model="password"
      />
      <span class="cursor-pointer" @click="showPassword = !showPassword">
        <Icon :name="showPassword ? 'eye_close' : 'eye_open'" />
      </span>
      <button class="cursor-pointer" @click="copyToClipboard"><Icon name="copy" /></button>
      <span v-text="status"></span>
    </div>
  </div>
</template>

<script>
import Icon from "../shared/Icon.vue";
export default {
  components: { Icon },
  data() {
    return {
      showPassword: false,
      password: null,
      status: "",
    };
  },
  methods: {
    copyToClipboard() {
      let copyText = this.password;
      navigator.clipboard.writeText(copyText);
      this.status = "copied";
      setTimeout(() => {
        this.status = ''
      }, 1000);
    },
  },
};
</script>

<style scoped>
a {
  color: #42b983;
}
</style>
