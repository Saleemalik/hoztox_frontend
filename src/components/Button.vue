<template>
  <div :class="['button', className]">
    <div :class="['track', property1]">{{ text }}</div>
  </div>
</template>

<script>
import { defineProps } from "vue";

export default {
  name: "Button",
  props: {
    property1: {
      type: String,
      default: "big",
      validator: function (value) {
        return ["big", "medium", "small"].indexOf(value) !== -1;
      },
    },
    className: {
      type: String,
      default: "",
    },
    text: {
      type: String,
      default: "TRACK",
    },
  },
};
</script>


<style>
.button {
  all: unset;
  align-items: flex-start;
  background-color: var(--orange);
  border-radius: 8px;
  box-sizing: border-box;
  display: inline-flex;
  gap: 10px;
  padding: 18px 54px;
  position: relative;
}

.button .track {
  color: var(--white);
  margin-top: -1px;
  position: relative;
  white-space: nowrap;
  width: fit-content;
}

.button .medium {
  font-family: var(--BUTTON-font-family);
  font-size: var(--BUTTON-font-size);
  font-style: var(--BUTTON-font-style);
  font-weight: var(--BUTTON-font-weight);
  letter-spacing: var(--BUTTON-letter-spacing);
  line-height: var(--BUTTON-line-height);
}

.button .small {
  font-family: var(--SUB-HEADING-2-font-family);
  font-size: var(--SUB-HEADING-2-font-size);
  font-style: var(--SUB-HEADING-2-font-style);
  font-weight: var(--SUB-HEADING-2-font-weight);
  letter-spacing: var(--SUB-HEADING-2-letter-spacing);
  line-height: var(--SUB-HEADING-2-line-height);
}

.button .big {
  font-family: var(--SUB-HEADING-1-font-family);
  font-size: var(--SUB-HEADING-1-font-size);
  font-style: var(--SUB-HEADING-1-font-style);
  font-weight: var(--SUB-HEADING-1-font-weight);
  letter-spacing: var(--SUB-HEADING-1-letter-spacing);
  line-height: var(--SUB-HEADING-1-line-height);
}

</style>
