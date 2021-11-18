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
              In stock
            </h2>

            <div
              class="
                mt-6
                grid grid-cols-1
                gap-y-10 gap-x-6
                sm:grid-cols-2
                lg:grid-cols-4
              "
            >
                <Product name='Cannabis oil' type='chanvre' price='5000' />
                <Product name='Prickly pear oil' type='fig' price='5000' />
                <Product name='Apricot oil' type='abricot' price='5000' />
                <Product name='Citrus oil' type='citron' price='5000' />
                <Product name='Fenugreek oil' type='fenugrec' price='5000' />
                <Product name='Ricine oil' type='ricin' price='5000' />
            </div>
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
