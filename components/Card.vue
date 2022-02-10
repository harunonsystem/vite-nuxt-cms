<template>
  <div class="max-w-md py-4 px-8 bg-white shadow-lg rounded-lg my-2">
    <div>
      <h2 class="text-gray-800 text-3xl font-semibold">Design Tools</h2>
      <p class="mt-2 text-gray-600">Lorem ipsum dolor sit amet consectetur adipisicing elit. Quae dolores deserunt ea
        doloremque natus error, rerum quas odio quaerat nam ex commodi hic, suscipit in a veritatis pariatur minus
        consequuntur!</p>
    </div>
    <div class="flex justify-end mt-4">
      <a href="#" class="text-xl font-medium text-indigo-500">Submit</a>
    </div>
  </div>
</template>

<script>
export default {
  name: "SampleCard",
  methods: {
    sample() {
      this.$router.push({ path: "/sample", query: { id: 1 } });
    }
  }
};
</script>
