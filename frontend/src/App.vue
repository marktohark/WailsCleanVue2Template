<template>
  <div id="app">
    <Logo />
    <Result :result="result" />
    <InputBox @change="result = $event"/>
  </div>
</template>

<script>
import Logo from "@/components/Logo";
import Result from "@/components/Result";
import InputBox from "@/components/InputBox";
export default {
  name: 'App',
  data() {
    return {
      result: 'Please enter your name below 👇',
    }
  },
  components: {Logo, Result, InputBox},
}
</script>

<style>

</style>
