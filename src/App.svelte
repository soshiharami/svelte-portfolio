<Heder id="header"/>
<div>
    <About/>
</div>

<script lang="ts">
    import Heder from "./compornent/Heder.svelte";
    import About from "./compornent/About.svelte";
</script>

<style>
    #header{
        position:fixed;
        top:0;
        margin:0;
        padding:4px;
        width:100%;
        background-color:#ccc;
        z-index:9999;
        height:50px;
    }
    div{
        height:100px;
    }
    input, button, textarea, select {
        -webkit-appearance: none;
        -moz-appearance: none;
        appearance: none;
    }
</style>
