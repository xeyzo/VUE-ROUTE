<template>
<div class="bg-gray-200 p-4">
  <p>{{ body }}</p>
</div>
</template>

<script>
export default {
    name:"PostList",
    props:["userId", "id", "title", "body"],
}
</script>