<script lang="ts">
    export let title: string;
    export let desc: string;
</script>

<article id="cover">
    <div>
        <h1>
            {title}
        </h1>
    </div>
    <div>
        <b>
            {desc}
        </b>
    </div>
</article>

<style lang="less">
    #cover {
        display: flex;
        flex-direction: column;
        align-items: center;
        justify-content: center;
        height: 100vh;

        & h1 {
            margin: 0;
        }
    }
</style>