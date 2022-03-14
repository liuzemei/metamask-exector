<script setup lang="ts">
import { onMounted, reactive, ref } from 'vue'
import { formatEth, getContract, getSigner } from '../ethers';
import { NButton, NForm, NFormItem, NInput, NRow, NCol, NStatistic, NIcon, useLoadingBar } from 'naive-ui'
import Header from './header.vue'
import Form from './form.vue'
const loadingBar = useLoadingBar()
// onMounted(() => {
// })


async function clickExec() {
  console.log()
  // execContract(JSON.parse(abi.value), contractAddress.value, 'addLiquidity', [address.value, amount.value])

}

</script>

<template>
  <Header />
  <Form />
</template>

