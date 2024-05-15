<template>
   <div class="overflow">
        <div class="threem">
          <a href="#">Over 3 million ready-to-work creatives!</a>
        </div>
      </div>
</template>

<script>
    export default {
        
    }
</script>

<style  scoped>
.threem {
  padding: 6px 12px;
  border-radius: 9999999px;
  -webkit-animation: over 32s linear infinite;
  animation: over 32s linear infinite;
}

.threem>a {
  text-decoration: none;
  color: #3d3d4e;
  font-family: "Source Serif 4", Georgia, serif;
  -webkit-transition: color 200ms ease;
  transition: color 200ms ease;
  color: #0d0c22;
  text-decoration: none;


}
@keyframes over {
  0% {
    background-color: #ffda79;
  }

  25% {
    background-color: #ffabe7;
  }

  50% {
    background-color: #d2bcf3;
  }

  75% {
    background-color: #edf3d8;
  }

  100% {
    background-color: #ffda79;
  }
}
</style>