<template>
  <div>
    This is child component.
    <h1>{{ text }}</h1>
  </div>
</template>


<script>
export default {
  name: 'ChildComponent',
  props: {
    text: {
      type: String,
      required: true,
    }
  }
}
</script>