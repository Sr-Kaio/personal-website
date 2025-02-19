<script>
    import { Github, Youtube, Twitter } from 'lucide-svelte';
</script>

<style>
    .button-text {
        text-shadow: 4px 4px 0px var(--color-primary);
        transition-duration: 200ms;
    }
    .button-icon {
        transition-duration: 200ms;
        color: var(--color-primary);
    }
    .button:hover .button-icon {
        color: var(--color-text);
    }
    .button:hover .button-text {
        text-shadow: 0px 0px 0px rgba(0, 0, 0, 0);
        color: var(--color-background);
    }
</style>

<main class="w-screen h-screen flex justify-center items-center flex-col p-6">
    <div class="w-screen max-w-6xl mb-12">
        <div class="border-b-2 border-text/15 bg-black/0 cursor-pointer w-full flex md:justify-between justify-center items-center hover:border-text/0 p-10 hover:bg-primary/70 duration-200 button">
            <p class="font-['Inter'] font-black italic md:text-8xl text-6xl button-text">
                /ART
            </p>
            <p class="text-text/50 w-64 md:block hidden">
                Section that is focused to my artistic side
            </p>
            <span class="md:block hidden">
                <span class="material-symbols-outlined button-icon ">
                    arrow_outward
                </span>
            </span>
        </div>
        <div class="border-b-2 border-text/15 bg-black/0 cursor-pointer w-full flex md:justify-between justify-center items-center hover:border-text/0 p-10 hover:bg-primary/70 duration-200 button">
            <p class="font-['Inter'] font-black italic md:text-8xl text-6xl button-text">
                /DEV
            </p>
            <p class="text-text/50 w-64 md:block hidden">
                Section that is focused to my developer side
            </p>
            <span class="md:block hidden">
                <span class="material-symbols-outlined button-icon ">
                    arrow_outward
                </span>
            </span>
        </div>
        <div class="border-b-2 border-text/15 bg-black/0 cursor-pointer w-full flex md:justify-between justify-center items-center hover:border-text/0 p-10 hover:bg-primary/70 duration-200 button">
            <p class="font-['Inter'] font-black italic md:text-8xl text-6xl button-text">
                /EDIT
            </p>
            <p class="text-text/50 w-64 md:block hidden">
                Section that is focused to my video editor / motion graphics side
            </p>
            <span class="md:block hidden">
                <span class="material-symbols-outlined button-icon ">
                    arrow_outward
                </span>
            </span>
        </div>
        <div class="border-b-2 border-text/15 bg-black/0 cursor-pointer w-full flex md:justify-between justify-center items-center hover:border-text/0 p-10 hover:bg-primary/70 duration-200 button">
            <p class="font-['Inter'] font-black italic md:text-8xl text-6xl button-text">
                /GAME
            </p>
            <p class="text-text/50 w-64 md:block hidden">
                List of my gawmes :3
            </p>
            <span class="md:block hidden">
                <span class="material-symbols-outlined button-icon">
                    arrow_outward
                </span>
            </span>
        </div>
    </div>
    <div class="flex gap-3.5">
        <a href="https://github.com/Sr-Kaio" class="cursor-pointer">
            <Github class="text-text/50 hover:text-primary duration-200 size-8"/>
        </a>
        <a href="https://www.youtube.com/@sr_kaio" class="cursor-pointer">
            <Youtube class="text-text/50 hover:text-primary duration-200 size-8"/>
        </a>
        <a href="https://x.com/SrKaio05497576" class="cursor-pointer">
            <Twitter class="text-text/50 hover:text-primary duration-200 size-8"/>
        </a>
    </div>
</main>