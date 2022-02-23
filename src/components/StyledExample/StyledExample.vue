<template>
  <StyledTag>
    {{ msg }}
  </StyledTag>
</template>

<script>
import { StyledTag } from "./styled";

export default {
  name: "StyledExample",
  components: { StyledTag },
  props: {
    msg: String,
  },
};
</script>
