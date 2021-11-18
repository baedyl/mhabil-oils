<template>
  <div class="group relative">
    <div
      class="
        w-full
        min-h-80
        bg-gray-200
        aspect-w-1 aspect-h-1
        rounded-md
        overflow-hidden
        group-hover:opacity-75
        lg:h-80 lg:aspect-none
      "
    >
      <img
        :src="image"
        rel="preload"
        alt="product's content"
        class="w-full h-full object-center object-cover lg:w-full lg:h-full"
      />
    </div>
    <div class="mt-4 flex justify-between">
      <div>
        <h3 class="text-sm text-gray-700">
          <a href="#">
            <span aria-hidden="true" class="absolute inset-0"></span>
            {{ name }}
          </a>
        </h3>
        <p class="mt-1 text-sm text-gray-500">{{ option }}</p>
      </div>
      <p class="text-sm font-medium text-gray-900">{{ price }} FCFA</p>
    </div>
  </div>
</template>

<script>
import chanvreOilImg from '@/assets/images/chanvre.jpg'

export default {
  components: {
    chanvreOilImg,
  },
  props: {
      type: {
          type: String,
          default: 'chanvre',
      },
      name: {
          type: String,
          default: 'Essential oil',
      },
      price: {
          type: Number,
          default: 0,
      },
      option: {
          type: String,
          default: '60 ml',
      }
  },
  computed: {
      image() {
          if (this.type === 'chanvre') {
              return chanvreOilImg
          } else if (this.type === 'fig') {
              return require('@/assets/images/figue.jpg')
          } else if (this.type === 'citron') {
              return require('@/assets/images/citron.jpg')
          } else if (this.type === 'abricot') {
              return require('@/assets/images/abricot.jpg')
          } else if (this.type === 'fenugrec') {
              return require('@/assets/images/fenugrec.jpg')
          } else if (this.type === 'ricin') {
              return require('@/assets/images/ricin.jpg')
          }
      }
  }
};
</script>
