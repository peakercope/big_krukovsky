<script lang="ts">
  export let title: string;
  export let desc: string;
</script>

<article id="cover" class="cover">
  <div>
    <h1 class="cover__title">
      {title}
    </h1>
  </div>
  <div>
    <b>
      {desc}
    </b>
  </div>
</article>

<style>
  .cover {
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    height: 100vh;
  }

  .cover__title {
    margin: 0;
  }
</style>
