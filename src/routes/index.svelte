<script>
</script>

<main class="absolute grid right-0 w-full min-h-screen bg-black duration-700 z-10">
    <video class="absolute top-0 left-0 w-full h-full object-cover opacity-80" src="./static/background-video.mp4" muted loop autoplay />
    <div
       id="glass" class="relative z-20 m-auto flex p-14 h-4/6 w-4/6 bg-transparent backdrop-blur-md rounded-3xl"
    >
        <div class="self-center w-2/4">
            <h1 class="text-white text-6xl font-bold mb-2">Lucas Fransson</h1>
            <h2 class="text-white text-4xl font-semibold mb-4">Web Developer</h2>
            <p class="text-white leading-relaxed text-xl mb-4">
                I’m a Front-End Developer with a passion for design, a good user experience and a
                user-friendly interface
            </p>
            <div class="flex w-1/3 justify-between">
                <button class="bg-white text-base font-medium text-black p-3 rounded-2xl">Contact</button>
                <button class="text-white font-medium text-base">My work</button>
            </div>
        </div>
        <div class="w-2/4 rounded-2xl" id="hero-container" />
    </div>
</main>

<style>
	#hero-container {
		background-image: url(./static/hero-image.jpg);
		background-position: center;
		background-repeat: no-repeat;
		background-size: cover;
	}

    #glass{
        -webkit-box-shadow: 0px 10px 25px 5px rgba(0,0,0,0.5); 
        box-shadow: 0px 10px 25px 10px rgba(0,0,0,0.7);
        border: 1px solid rgba(255, 255, 255, 0.1);
    }
</style>
