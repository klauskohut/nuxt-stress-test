<template>
  <div class="wrapper">
    <button @click="prev" class="prev"><</button>
    <button @click="next" class="next">></button>
    <div>
      <transition-group name="fade" tag="div">
        <div v-for="i in [currentIndex]" :key="i">
          <img :src="currentImg.src" />
        </div>
      </transition-group>
    </div>
  </div>
</template>

<script>
export default {
  data: function() {
    return {
      timer: null,
      currentIndex: 0,
      slides: [
        {
          src:
            'https://images.unsplash.com/photo-1568968107682-40c48d6af623?crop=entropy&cs=tinysrgb&fit=crop&fm=jpg&h=300&ixlib=rb-1.2.1&q=80&w=500',
          title: 'Window'
        },
        {
          src:
            'https://images.unsplash.com/photo-1568185518838-3300c90c9170?crop=entropy&cs=tinysrgb&fit=crop&fm=jpg&h=300&ixlib=rb-1.2.1&q=80&w=500',
          title: 'Laptop'
        },
        {
          src:
            'https://images.unsplash.com/photo-1570145820386-15a56730192c?crop=entropy&cs=tinysrgb&fit=crop&fm=jpg&h=300&ixlib=rb-1.2.1&q=80&w=500',
          title: 'Food'
        }
      ]
    }
  },
  mounted: function() {
    this.startSlide()
  },
  beforeDestroy: function() {
    clearInterval(this.timer)
  },
  methods: {
    startSlide: function() {
      if (this.timer) clearInterval(this.timer)

      this.timer = setInterval(this.next, 4000)
    },
    next: function() {
      this.startSlide()
      this.currentIndex += 1
    },
    prev: function() {
      this.startSlide()
      this.currentIndex -= 1
    }
  },
  computed: {
    currentImg: function() {
      return this.slides[Math.abs(this.currentIndex) % this.slides.length]
    }
  }
}
</script>

<style scoped>
.wrapper {
  position: relative;
  height: 300px;
  width: 500px;
}

.next,
.prev {
  position: absolute;
  top: calc(50% - 12px);

  height: 24px;
  border-radius: 24px;
}

.next {
  right: 0;
}

.fade-enter-active,
.fade-leave-active {
  transition: all 0.9s ease;
  overflow: hidden;
  visibility: visible;
  position: absolute;
  width: 100%;
  opacity: 1;
}

.fade-enter,
.fade-leave-to {
  visibility: hidden;
  width: 100%;
  opacity: 0;
}

img {
  height: 300px;
  width: 100%;
}
</style>
