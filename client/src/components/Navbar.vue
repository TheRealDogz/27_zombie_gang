<template>

    <div class="flex flex-col">
        <div class="flex flex-row items-center text-left h-20 bg-green-400">
            <p class="text-white px-10">27ZG SIUUUUUm</p> 
        </div>
        <div class="flex flex-row justify-center space-x-60 pt-16">
            <div class="flex flex-col">
                <div class="flex items-center justify-center bg-gray-300 h-52 w-52 rounded-lg shadow-2xl">
                    <span class="material-icons text-white text-9xl">
                        thermostat
                    </span>
                </div>
                <div class="flex pt-5 justify-center">
                    <button class="px-5 border-2 border-green-400 rounded-lg">
                        Grafico temperatura
                    </button>
                </div>
            </div>
            <div class="flex flex-col">
                <div class="flex items-center justify-center bg-gray-300 h-52 w-52 rounded-lg shadow-2xl">
                    <span class="material-icons text-white text-9xl">
                        volume_up
                    </span>
                </div>
                <div class="flex pt-5 justify-center">
                    <button class="px-5 border-2 border-green-400 rounded-lg">
                        Grafico rumore
                    </button>
                </div>
            </div>
            <div class="flex flex-col">
                <div class="flex items-center justify-center bg-gray-300 h-52 w-52 rounded-lg shadow-2xl">
                    <span class="material-icons text-white text-9xl">
                        water_drop
                    </span>
                </div>
                <div class="flex pt-5 justify-center">
                    <button class="px-5 border-2 border-green-400 rounded-lg">
                        Grafico umidità
                    </button>
                </div>
            </div>
        </div>
    </div>

</template>

<script>
export default {
}
</script>
