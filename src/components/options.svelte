<script lang="ts">
    export let options: {
        title: string
        desc: string
    }[];
</script>

<article id="options">
  {#each options as option}
    <h3>
      { option.title }
    </h3>
    <h4>
      { option.desc }
    </h4>
  {/each}
</article>

<style lang="less">
  #options {
    height: 100vh;
  }
</style>