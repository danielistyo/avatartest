<template>
  <mp-box padding-y="4">
    <mp-tooltip id="tooltip-default" label="Default" position="right">
      <mp-avatar name="Rizal Chandra" src="https://i.pravatar.cc/300" size="md" margin-right="2" :show-border="false" />
    </mp-tooltip>
  </mp-box>
</template>

<script>
import { MpBox, MpAvatar, MpTooltip } from "@mekari/pixel";

export default {
  name: "AvatarWithTooltip",
  components: { MpBox, MpAvatar, MpTooltip },
};
</script>
