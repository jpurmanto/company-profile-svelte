<script>
  import { Splide, SplideSlide } from '@splidejs/svelte-splide';
  import '@splidejs/svelte-splide/css';
</script>

<Splide aria-label="My Favorite Images">
  <SplideSlide>
    <img src="src/night_at_the_lake_by_notthatcherry_dfvdp21.png" alt="Image 1"/>
  </SplideSlide>
  <SplideSlide>
    <img src="src/night_walk_of_dream_by_notthatcherry_dfvp5uf.png" alt="Image 2"/>
  </SplideSlide>
</Splide>

<style lang="postcss">
  :global(html) {
    background-color: theme(colors.gray.100);
  }
</style>
