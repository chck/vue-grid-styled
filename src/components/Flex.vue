<script>
import { Flex } from "./styles";

export default {
  name: "flex",
  functional: true,
  render(h, { props, children, parent }) {
    return h(Box(props, parent.$vgsTheme), children);
  }
};
</script>
