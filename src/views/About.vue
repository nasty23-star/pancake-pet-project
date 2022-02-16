<template>
<div class="container">
  <div class="english">
   
   <button @click="getFinal">get in english</button>
      <div class="final">{{final}}</div>
  </div>
  </div>
 
</template>

<script>


export default {
data() {
    return {
    final: "",
      items: ["Anything Less Than Immortality Is A Complete Waste Of Time.", "This Is The Worst Kind Of Discrimination There Is: The Kind Against Me!", "I’m So Embarrassed. I Wish Everybody Else Was Dead.", "Bite My Shiny Metal Ass!", "How Can I Be So Bad At Everything I Try, And Still Be So Great?", "I will destroy you!", "Attention passengers please remain seated until the plane comes to a complete crash.", "Just shut up and take my money!"]
  }
},
methods: {
getFinal() {

        let idx = [Math.floor(Math.random()*this.items.length)]
        this.final = this.items[idx]
       }
}
}
</script>
<style>


</style>