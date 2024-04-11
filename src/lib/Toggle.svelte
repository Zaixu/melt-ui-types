<script lang="ts">
    import { createToggle, melt } from '@melt-ui/svelte';
	import Button from './Button.svelte';
  
    const {
      elements: { root },
    } = createToggle();
  </script>
  
  <Button element={root}>
    ABC
  </Button>