<template>
  <div class="home">
    <HelloWorld msg="Welcome to Your Vue.js App"/>
    <div class="display">
      <div class="row">
        <div class="col"></div>
      </div>
    </div>
  </div>
</template>

<script>

// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'
import footer from '@/components/footer.vue'
import cars from '@cars.json'
export default {
  name: 'HomeView',
  components: {
    HelloWorld,footer
  },
//DOM manupilation

}
for (let cars = 0; i < cars.length; cars++) {
  
}
col.innerHTML+=`<div class="card" style="width: 18rem;">
  <img src="${cars.image}" class="card-img-top">
  <div class="card-body">
    <h5 class="card-title">${cars.name}</h5>
    <p class="card-text">${cars.modal}</p>
    <a href="#" class="btn btn-primary">Go somewhere</a>
  </div>
</div>`
</script>
