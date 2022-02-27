<script>

</script>

<main class="flex justify-center items-center min-h-screen fixed bg-black">
    <!-- svelte-ignore a11y-media-has-caption -->
    <video class="opacity-50" src="./static/background-video.mp4" muted loop autoplay></video>
    <div class="absolute shadow-md shadow-neutral-600 flex p-10 h-4/6 w-4/6 bg-transparent backdrop-blur-md rounded-3xl">
        <div class="self-center w-2/4">
            <h1 class="text-white text-6xl font-bold">Lucas Fransson</h1>
            <p class="text-white leading-relaxed mt-3 text-xl">I’m a Front-End Developer with a passion for design, a good user experience and a user-friendly interface</p>
            <div class="flex w-1/3 justify-between m-auto">
                <button class="bg-white text-base font-medium text-black p-3 rounded-2xl">Contact</button>
                <button class="text-white font-medium text-base">My work</button>
            </div>
        </div>
        <div class="w-2/4 rounded-2xl" id="hero-container"></div>
    </div>
</main>

<style>
    #hero-container{
        background-image: url(./static/hero-image.jpg);
        background-position: center;
        background-repeat: no-repeat;
        background-size: cover;
    }
</style>