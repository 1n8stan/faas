<script setup>
import AuthenticatedLayout from "@/Layouts/AuthenticatedLayout.vue";
import { Head } from "@inertiajs/vue3";
</script>

<template>
    <Head title="Dashboard" />

    <AuthenticatedLayout>
        <template #header>
            <h2 class="text-xl font-semibold leading-tight text-gray-800">
                Dashboard
            </h2>
        </template>

        <div class="py-12">
            <div class="mx-auto max-w-7xl sm:px-6 lg:px-8">
                <div class="mockup-browser border-base-300 border w-full">
                    <div class="mockup-browser-toolbar">
                        <div class="input">https://daisyui.com</div>
                    </div>
                    <div
                        class="grid place-content-center border-t border-base-300 h-80"
                    >
                        Hello!
                    </div>
                </div>
                <div class="p-6 bg-primary text-primary-content rounded">
                    This should have a themed background!
                </div>
            </div>
        </div>
    </AuthenticatedLayout>
</template>
