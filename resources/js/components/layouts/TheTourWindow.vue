<template>
    <div class="mb-4 px-3 pb-4 pt-2 bg-gray-800 rounded-lg text-white justify-between">
        <div class="flex justify-end">
            <button>
                <img class="rounded hover:bg-gray-600 p-1" src="https://img.icons8.com/ios/20/9AF4EA/close-window.png"/>
            </button>
        </div>

        <div class="flex flex-row">
            <div class="flex flex-col space-y-1 w-9/12">
                <p class="text-teal-200">Stacja początkowa:</p>
                <p class="font-semibold">Nowy Dwor Mazowiecki (Nowy Dwór Mazowiecki)</p>
            </div>
            <button class="flex justify-end items-center mt-6 w-3/12" title="Usuń stację">
                <img class="rounded hover:bg-gray-600 py-2 px-1" src="https://img.icons8.com/ios/20/FFFFFF/delete--v1.png"/>
            </button>
        </div>
        <div class="flex flex-row">
            <div class="flex flex-col space-y-1 my-2 w-9/12">
                <p class="text-teal-200">Przez:</p>
                <p class="font-semibold">Aleksandrow Kujawski (Aleksandrów Kujawski)</p>
            </div>
            <button class="flex justify-end items-center mt-6 w-3/12" title="Usuń stację">
                <img class="rounded hover:bg-gray-600 py-2 px-1" src="https://img.icons8.com/ios/20/FFFFFF/delete--v1.png"/>
            </button>
        </div>
        <div class="flex flex-row">
            <div class="flex flex-col space-y-1 my-2 w-9/12">
                <p class="text-teal-200">Stacja końcowa:</p>
                <p class="font-semibold">Wałbrzych Miasto</p>
            </div>
            <button class="flex justify-end items-center mt-6 w-3/12" title="Usuń stację">
                <img class="rounded hover:bg-gray-600 py-2 px-1" src="https://img.icons8.com/ios/20/FFFFFF/delete--v1.png"/>
            </button>
        </div>

        <div class="flex flex-wrap flex-col items-center">
            <base-button class="bg-teal-400 hover:bg-teal-500 w-2/3 lg:w-7/12">Dodaj wycieczkę</base-button>
            <base-button class="bg-teal-600 hover:bg-teal-700 w-2/3 lg:w-7/12">Dodaj post</base-button>
        </div>

    </div>
</template>

<script>

export default {
    name: "TheTourWindow",
    components: {},

}
</script>

<style scoped>

</style>
