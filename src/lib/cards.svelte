<div class="bg-[#1CB9B9] w-80 h-fit rounded-b-[100px]">
    <div class="flex justify-center bg-black">
        <h1 class="text-2xl h-10 text-center capitalize">
            {title}
        </h1>
    </div>
    <img class="w-full h-[10rem]" alt={imageAlt} src="{imageUrl}">
    <div class="ml-2">
        <p class="font-semibold">{text}</p>
    </div>
    <br><br>
    <div class="flex justify-center">
        <button on:click={()=>window.open(urlOpen)} class="bg-black rounded-xl h-10 w-20 text-yellow-700">Explore</button>
    </div>
    <br>
</div>


<script lang="ts">
    let title: string;
    let text: string;
    let imageUrl: string;
    let imageAlt: string;
    let urlOpen: string;
    export {title, text, imageAlt, imageUrl, urlOpen};
</script>