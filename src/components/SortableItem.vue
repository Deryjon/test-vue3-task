<template>
    <div>
        <v-select
      :items="items"
      label="Default"
      class="bg-white-500"
      variant="solo"
    ></v-select>
    </div>
  </template>
  
  <script>
  export default {
    data: () => ({
      items: ['Foo', 'Bar', 'Fizz', 'Buzz'],
    }),
  }
</script>
  