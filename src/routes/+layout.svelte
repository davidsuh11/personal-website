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
        color: inherit;
    }
</style>
<svelte:head>
    <meta name="viewport" 
    content="width=device-width, initial-scale=0.50, maximum-scale=1">
</svelte:head>
<div class = "bg-zinc-900 m-0 w-full">
    <div class='flex gap-4 flex-row p-1 bg-inherit items-center'>
        <p class="bg-inherit font-mono font-extrabold p-1"> d\h.suh </p>
        <nav class = "flex gap-4 bg-inherit">
            <a href="/" class='hover:italic'>home</a>
            <a href="/about" class='hover:italic'>about</a>
            <a href="/projects" class='hover:italic'>projects</a>
            <a href="/resume" class='hover:italic'>cv/resume</a>
            <a href="/blog" class='hover:italic'>blog</a>


        </nav>
        <div class='grow bg-inherit'></div>
        <a href="/hireme" class="self-end bg-inherit text-inherit p-1 font-bold">🧑🏻‍💻 hire me!</a>
    </div>   
</div>


<slot />
