<template>
  <div>
    <Header />
    <Buttons />
    <Divider />
    <div class="tables">
      <Table />
      <Table />
      <Table />
      <Table />
    </div>
  </div>
</template>

<script>
import Header from "@/components/Header";
import Table from "@/components/Table";

import Buttons from "@/views/Buttons";
import Divider from "@/views/Divider";

export default {
  name: "main-component",
  components: {
    Header,
    Buttons,
    Divider,
    Table,
  },
};
</script>
