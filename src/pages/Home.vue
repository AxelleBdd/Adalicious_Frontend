<template>
    <body class="bg-white text-black m-50">
        <header class="relative w-full h-20">
            <button class="absolute top-4 right-4 bg-black text-white px-4 py-2 rounded cursor-pointer">Kitchen interface 🍴</button>
        </header>
        <main class="flex flex-col bg-center m-50">
            <h1>🥦</h1>
            <h2 class="space-x-10">Welcome to Adalicious</h2>
            <p class="space-x-10">to start, please enter your name:</p>
            <form action="submit" class="space-x-10">
                <input type="text" class="shadow appearance-none border rounded w-full py-2 px-3 text-gray-700 leading-tight focus:outline-none focus:shadow-outline">
                <button type="submit" class="bg-blue-400 text-white px-4 py-2 rounded cursor-pointer">Submit</button>
            </form>
        </main>
    </body>
</template>

<script>
    export default {
  name: "Home"}
</script>

<style>
</style>