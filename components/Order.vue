<template>
  <div class="relative bg-white overflow-hidden">
    <div class="max-w-7xl mx-auto">
      <div
        class="
          relative
          z-10
          pb-8
          bg-white
          sm:pb-16
          md:pb-20
          xl:pb-10
        "
      >
        <MhabilLogo class="lg:block right-0 inset-y-0 h-full" />
        <main>
          <div
            class="
              mx-auto
              px-4
              sm:px-6
            "
          >
            <h2 class="text-2xl font-extrabold tracking-tight text-gray-900">
              Order via whatsapp at: +237 6 94 95 75 84
            </h2>
          </div>
        </main>
      </div>
    </div>
  </div>
</template>

<script>
import MhabilLogo from "./MhabilLogo";
import Product from './Product';

export default {
  components: {
    MhabilLogo,
    Product
  },
};
</script>
