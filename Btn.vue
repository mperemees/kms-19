<template>
<button class="button" :class="{
  'is-primary': primary,
  'is-info': info,
  'is-white': white,
  'is-light': light,
  'is-dark': dark,
  'is-black': black,
  'is-text': text,
  'is-ghost': ghost,
  'is-link': link,
  'is-success': success,
  'is-warning': warning,
  'is-danger': danger,
  'is-small': small,
  'is-normal': normal,
  'is-medium': medium,
  'is-large': large,
  'is-fullwidth': fullwidth,
  'is-outlined': outlined,
  'is-inverted': inverted,
  'is-rounded': rounded,
  'is-hovered': hovered,
  'is-focused': focused,
  'is-active': active,
  'is-loading': loading,
  'is-static': staticButton,
  'is-disabled': disabled,
}"><slot></slot></button>
</template>

<script>
export default {
name: "Btn",
  props: {
    primary: Boolean,
    info: Boolean,
    white: Boolean,
    light: Boolean,
    dark: Boolean,
    black: Boolean,
    text: Boolean,
    ghost: Boolean,
    link: Boolean,
    success: Boolean,
    warning: Boolean,
    danger: Boolean,
    small: Boolean,
    normal: Boolean,
    medium: Boolean,
    large: Boolean,
    fullwidth: Boolean,
    outlined: Boolean,
    inverted: Boolean,
    rounded: Boolean,
    hovered: Boolean,
    focused: Boolean,
    active: Boolean,
    loading: Boolean,
    staticButton: Boolean,
    disabled: Boolean,
  }
}
</script>

<style scoped>

.button{
  margin-top: 20px;
}

</style>