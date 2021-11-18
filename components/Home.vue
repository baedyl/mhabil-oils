<template>
  <!-- This example requires Tailwind CSS v2.0+ -->
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
          lg:max-w-2xl lg:w-full lg:pb-10
          xl:pb-10
        "
      >
        <MhabilLogo class="lg:block right-0 inset-y-0 h-full" />
        <main
          class="
            mx-auto
            max-w-7xl
            px-4
            sm:mt-12 sm:px-6
            md:mt-16
            lg:mt-10 lg:px-8
          "
        >
          <div class="sm:text-center lg:text-left">
            <h1
              class="
                text-4xl
                tracking-tight
                font-extrabold
                text-gray-900
                sm:text-5xl
                md:text-6xl
              "
            >
              <span class="block xl:inline">Oils to enrich your</span>
              <span class="block text-primary xl:inline"
                >amazing life</span
              >
            </h1>
            <p
              class="
                text-base text-gray-500
                sm:mt-5 sm:text-lg sm:max-w-xl sm:mx-auto
                md:mt-5 md:text-xl
                lg:mx-0
              "
            >
              Our oils contain a large number of healing properties, 
              including antioxidant and anti-inflammatory properties. 
              Both help reduces symptoms for a number of different inflammatory skin conditions like reddishness and itchy skin. 
              </br>For best results, apply our oils directly to the damaged areas.
            </p>
            <div
              class="mt-5 sm:mt-8 sm:flex sm:justify-center lg:justify-start"
            >
              <div class="rounded-md shadow">
                <a
                  href="/catalogue"
                  class="
                    w-full
                    flex
                    items-center
                    justify-center
                    px-8
                    py-3
                    border border-transparent
                    text-base
                    font-medium
                    rounded-md
                    text-white
                    bg-primary
                    hover:bg-purple-400
                    md:py-4 md:text-lg md:px-10
                  "
                >
                  View products
                </a>
              </div>
              <div class="mt-3 sm:mt-0 sm:ml-3">
                <a
                  href="order"
                  class="
                    w-full
                    flex
                    items-center
                    justify-center
                    px-8
                    py-3
                    border border-transparent
                    text-base
                    font-medium
                    rounded-md
                    text-primary
                    bg-purple-100
                    hover:bg-purple-200
                    md:py-4 md:text-lg md:px-10
                  "
                >
                  Order now
                </a>
              </div>
            </div>
          </div>
        </main>
      </div>
    </div>
    <div class="lg:absolute lg:inset-y-0 lg:right-0 lg:w-1/2">
      <img
        class="h-56 w-full object-cover sm:h-72 md:h-96 lg:w-full lg:h-full"
        src="https://images.unsplash.com/photo-1560521166-5e3fce3b3d39?ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&ixlib=rb-1.2.1&auto=format&fit=crop&w=1170&q=80"
        alt=""
      />
    </div>
  </div>
</template>

<script>
import MhabilLogo from './MhabilLogo'

export default {
  components: {
    MhabilLogo,
  },
}
</script>
