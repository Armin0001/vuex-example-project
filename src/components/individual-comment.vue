<!-- eslint-disable prettier/prettier -->

<template>
  <div>
    <li>
      <img class="post-img" :src="commentpost.authorImg" />
      <small>{{ commentpost.author }}</small>
      <p class="post-comment">"{{ commentpost.text }}"</p>
    </li>
  </div>
</template>
<!-- eslint-disable prettier/prettier -->
<script>
export default {
  name: "IndividualComment",
  template: "#comment-template",
  props: ["commentpost"],
};
</script>
