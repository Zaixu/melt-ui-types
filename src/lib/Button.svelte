<script lang="ts">
    import { type AnyMeltElement, emptyMeltElement } from '@melt-ui/svelte'

    export let element: AnyMeltElement = emptyMeltElement
</script>

<button {...$element} use:element class="grid h-9 w-9 place-items-center items-center justify-center rounded-md
bg-white text-base leading-4 text-magnum-800 shadow-lg hover:bg-magnum-100
  data-[disabled]:cursor-not-allowed data-[state=on]:bg-magnum-200
  data-[state=on]:text-magnum-900">
    <slot />
</button>