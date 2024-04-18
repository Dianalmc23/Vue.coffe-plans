<template>
    <div class="plan">
         <div class="description">
           <span class="title">
             {{ name }} 
          </span>
      </div>
     </div>
 </template>
 <script setup>
  defineProps ({
name: {
type: String,
default: "true",
}
});
 </script>
  
 <style lang="scss" scoped>
  
 </style>
 tiene menú contextual