<template>
    <div class="max-w-md mx-auto my-20">
        <div class="bg-white p-4 sm:p-8 rounded mx-4">
            <h2 class="text-center font-semibold text-2xl text-gray-700 mb-6">LOGIN</h2>
            <form>
                <div class="mb-5">
                    <label for="email" class="block mb-2 text-lg font-medium text-gray-900 dark:text-white">Seu email</label>
                    <input type="email" id="email" class="bg-gray-50 border border-gray-300 text-gray-900 text-sm rounded-lg focus:ring-blue-500 focus:border-blue-500 block w-full p-2.5 dark:bg-gray-700 dark:border-gray-600 dark:placeholder-gray-400 dark:text-white dark:focus:ring-blue-500 dark:focus:border-blue-500" placeholder="name@dominio.com" required />
                </div>
                <div class="mb-5">
                    <label for="password" class="block mb-2 text-lg font-medium text-gray-900 dark:text-white">Sua senha</label>
                    <input type="password" id="password" class="bg-gray-50 border border-gray-300 text-gray-900 text-sm rounded-lg focus:ring-blue-500 focus:border-blue-500 block w-full p-2.5 dark:bg-gray-700 dark:border-gray-600 dark:placeholder-gray-400 dark:text-white dark:focus:ring-blue-500 dark:focus:border-blue-500" required />
                </div>
                <div class="flex items-center justify-between mb-5">
                    <div class="flex items-start">
                        <div class="flex items-center h-5">
                            <input id="remember" type="checkbox" value="" class="w-4 h-4 border border-gray-300 rounded bg-gray-50 focus:ring-3 focus:ring-blue-300 dark:bg-gray-700 dark:border-gray-600 dark:focus:ring-blue-600 dark:ring-offset-gray-800 dark:focus:ring-offset-gray-800" />
                        </div>
                        <label for="remember" class="ms-2 text-sm font-medium text-gray-900 dark:text-gray-300">Lembre de mim</label>
                    </div>
                    <div>
                        <a href="/auth/forgot" class="font-medium text-blue-600 dark:text-blue-500 underline hover:no-underline">Esqueci minha senha</a>
                    </div>
                </div>
                <button type="submit" class="text-base font-medium text-white bg-blue-700 hover:bg-blue-800 focus:ring-4 focus:outline-none focus:ring-blue-300 rounded-lg w-full sm:w-auto px-5 py-2.5 text-center dark:bg-blue-600 dark:hover:bg-blue-700 dark:focus:ring-blue-800">
                    Entrar
                </button>
            </form>
        </div>
    </div>
</template>

<script setup lang="ts">

definePageMeta({
    layout: 'guest'
});

</script>

<style lang="css" scoped>

</style>