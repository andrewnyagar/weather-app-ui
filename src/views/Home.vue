<template>

  <b-container>
    <b-row align-h="center" cols="1">
      <b-col class="flex-grow-0"> <Heading /></b-col>
      <b-col  class="d-flex justify-content-center"> <Icon /></b-col>
      <b-col class="flex-grow-0"> <Detail /></b-col>
      <b-col class="flex-grow-0"><Form /></b-col>
    </b-row>
  </b-container>
</template>

<script>
import Heading from "../components/Heading";
import Icon from "../components/Icon";
import Detail from "../components/Detail";
import Form from "../components/Form";
export default {
  components: {
    Heading,
    Icon,
    Detail,
    Form
  }
};
</script>


<style lang="scss" scoped>
</style>