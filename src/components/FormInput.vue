<template>
  <div>
    <input
      type="text"
      name=""
      id=""
      class="border rounded-md h-12 w-48"
      :value="modelValue"
      @input="$emit('update:modelValue', $event.target.value)"
    /><br />
    <slot></slot>
  </div>
</template>
<script>
let id = 0;
export default {
  props: ["modelValue"],
  emits: ["update:modelValue"],
  data() {
    return {};
  },
  methods: {},
};
</script>
