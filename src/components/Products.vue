
    <template>
  <div>
    <div class="card-deck row m-auto">
      <div v-for="product in products" :key="product" class="card m-5 p-0" style="width: 25rem;">
        <img :src=product.image class="">
        <div class="card-body bg">
          <p class="card-title">{{ product.name }}</p>
          <p class="card-text">{{ product.price }}</p>
        </div>
      </div>
    </div>
  </div>
</template>
  
  <script>
  export default {
    data() {
      return {
        products: [
            {
                image : "https://i.postimg.cc/mDz9Sr51/DALL-E-2022-12-14-09-12-47-purple-sunset-digital-art.png",
                name : "Purple Sunset",
                price: 1200
            },
            {
              image : "https://i.postimg.cc/7Y8VdPK3/DALL-E-2022-12-14-08-52-39-a-bowl-of-soup-that-is-also-a-portal-to-another-dimension-digital-art.png",
              name : "Portal",
              price: 1550   
            },
            {
              image : "https://i.postimg.cc/kGvmrJtT/DALL-E-2022-12-14-09-05-03-CAT-AND-LAPTOP-DIGITAL-ART.png",
              name : "Cat coding",
              price: 1320   
            },
            {
              image : "https://i.postimg.cc/BZRqtf16/DALL-E-2022-12-14-09-30-00-a-digital-art-of-a-purple-time-machine.png",
              name : "The Shining",
              price: 1680   
            },
            {
              image : "https://i.postimg.cc/wMYRXybf/DALL-E-2022-12-14-09-33-31-a-digital-art-of-a-purple-time-machine.png",
              name : "Time Machine",
              price: 1680   
            },
            {
              image : "https://i.postimg.cc/SRgFm1jb/DALL-E-2022-12-14-09-36-02-purple-sunset-digital-art.png",
              name : "Purple Planet",
              price: 2000   
            },
        ]
        
      }
    }
  }
  </script>

<style scoped>
.card-body {
  font-family: 'Josefin Slab', serif;
  font-size: larger;
}
</style>  