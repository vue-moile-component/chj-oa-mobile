<template>
  <div class="md-example-child md-example-child-slider">
    <md-textarea></md-textarea>
	</div>
</template>

<script>import {Textarea} from 'mand-mobile'

export default {
  name: 'textarea-demo',
  /* DELETE */
  title: '基本',
  titleEnUS: 'Basic',
  /* DELETE */
  components: {
    [Textarea.name]: Textarea,
  },
}
</script>
