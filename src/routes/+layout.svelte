<script>
    import "../app.css";
</script>
<style>

    nav {
        font-size: 10px;
        margin: 1em;
        display: flex;
    }
    nav a{
        flex-grow:0;
        font-size: 24px;
        background: inherit;
    }
</style>
<div class = "bg-zinc-900 m-0">
    <div class='flex gap-4 flex-row p-1 bg-inherit content-start'>
        <p class="bg-inherit font-serif p-1"> david h. suh </p>
        <nav class = "gap-4 bg-inherit">
            <a href="/">home</a>
            <a href="/about">about</a>
            <a href="/projects">projects</a>
            <a href="/resume">cv/resume</a>
        </nav>
    </div>   
</div>


<slot />
