<template>
  <div id="app">
    <zoomable>
      <div style="width: 400px;
                height: 400px;">
        <img style="width: 100%;height: 100%;object-fit: cover;" src="https://cdn.shopeichlers.com/media/43690/conversions/vjo6oxvqt6rte6fn__main-toy-banner-02-1800.jpg" alt="">
      </div>
    </zoomable>
  </div>
</template>

<script>
import Zoomable from './components/Zoomable'

export default {
  name: 'App',
  components: {
    Zoomable
  }
}
</script>