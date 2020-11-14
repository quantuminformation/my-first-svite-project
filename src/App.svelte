<script>
    import { Router, Route, link } from "svelte-navigator"
    const world = "world" // edit world and save to see hmr update
    const about = "about" // edit world and save to see hmr update
</script>

<style>
    h1 {
        color: orangered; /* change color an save to see hmr update */
    }
</style>

<h1>Hello {world}</h1>
<p>Open App.svelte in your editor and change something to see HMR in actiond</p>

<Router>
    <Route path="about" component="{about}" />
</Router>
s
