<script>
    import { Router, Route, link } from "svelte-navigator"
    const world = "world" // edit world and save to see hmr update
    import about from "./about.svelte"
    import index from "./index.svelte"
</script>

<style>
    h1 {
        color: orangered; /* change color an save to see hmr update */
    }
</style>

<h1>Hello {world}</h1>
<p>Open App.svelte in your editor and change something to see HMR in action</p>

<Router>
    <Route path="/">
        <index></index>
    </Route>
    <Route path="/about" ><about></about></Route>
</Router>

