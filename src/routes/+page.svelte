<script>
    import { fade, scale } from 'svelte/transition';
    let occups = ['Computer Scientist', 'Mathematician', ' Software Engineer', 'Student']
    let occup = occups[0]
    let idx = 0;


    function update_occup() {
        let nxt = occups[idx];
        occup=nxt
        idx +=1
        idx = idx%4
    }
    setInterval(update_occup, 2500)
</script>
<style>

.wave {
    animation-name: waving-anim;
    animation-duration: 5s;
    animation-iteration-count: infinite;
    transform-origin: 70% 70%;
    display: inline-block;
}

@keyframes waving-anim {
    0% { transform: rotate( 0.0deg) }
   5% { transform: rotate(14.0deg) }
   10% { transform: rotate(-8.0deg) }
   15% { transform: rotate(14.0deg) }
   20% { transform: rotate(-4.0deg) }
   25% { transform: rotate(10.0deg) }
   30% { transform: rotate( 0.0deg) }
  100% { transform: rotate( 0.0deg) }
}
</style>
<div class='p-10 lg:p-12 lg:mx-32 mx-16'>
    <div class='h-80 text-center my-20'>    
        <span class='wave text-5xl'>👋</span><h1 class="text-5xl">Trying to live a good life.
        <br>
        <br>
        David Suh<sup>*</sup> <br><br>
        {#key occup}
        <sup class='text-xl'>*</sup><span class='text-3xl bg-transparent' in:fade="{{delay: 500, duration: 400}}" out:fade="{{duration: 400}}">{occup}</span>
        {/key}
    </h1>
    </div>

    <br><br>
    <p class='text-xl md:text-2xl'>I'm a student currently pursuing a Bachelors in Mathematics and Computer Science with a Masters in Computer Science at the University of Chicago. This is my website, which I host to keep track of my personal projects, to post a couple blogs, and provide other people with a more in depth look at my work. </p>
</div>

