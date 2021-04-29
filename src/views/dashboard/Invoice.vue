<template>
  <div class="page-invoice">
    <div class="column is-multiple">
      <div class="column is-12">
        <h1 class="title">Invoice -{{ invoice.invoice_number }}</h1>
      </div>
    </div>
  </div>
</template>

<script>
import axios from "axios";
export default {
  name: "Invoice",
  data() {
    return {
      invoice: {},
    };
  },
};
</script>

<style></style>
