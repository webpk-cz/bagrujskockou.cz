<template>

<hr class="border border-gray-400 rounded-full mx-5 mt-12" />

<footer class="my-5 p-4 text-sm flex flex-col lg:flex-row lg:items-center lg:justify-between lg:p-6">
    <span class="text-gray-600 sm:text-center max-w-prose lg:max-w-max">
        &copy; {{ new Date().getFullYear() }} Miroslav Doležal. Tato webová stránka není schválena, přímo spojena, udržována, autorizována ani sponzorována společností Bobcat CZ, a.s.
    </span>
    <ul class="flex flex-wrap items-center mt-3 text-sm text-gray-500 sm:mt-0 gap-4">
        <li>
            <a href="/#kontakt" class="hover:underline">Kontakt</a>
        </li>
        <li>
            <a target="_blank" href="/specifikace.pdf" class="hover:underline">Specifikace</a>
        </li>
    </ul>
</footer>

</template>
