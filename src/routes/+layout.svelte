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
<div class = "bg-zinc-900 m-0">
    <div class='flex gap-4 flex-row p-1 bg-inherit items-center'>
        <p class="bg-inherit font-serif p-1"> david h. suh </p>
        <nav class = "flex gap-4 bg-inherit">
            <a href="/">home</a>
            <a href="/about">about</a>
            <a href="/projects">projects</a>
            <a href="/resume">cv/resume</a>
            <a href="/blog">blog</a>


        </nav>
        <div class='grow bg-inherit'></div>
        <a href="/hireme" class="self-end bg-inherit text-inherit p-1 font-bold">🧑🏻‍💻 hire me!</a>
    </div>   
</div>


<slot />
