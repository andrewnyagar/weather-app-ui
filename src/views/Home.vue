<template>
  <div>
    <Heading />
    <Icon />
    <Form />
    <Detail />
  </div>
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