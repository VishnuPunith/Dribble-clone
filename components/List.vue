<template>
   <div class="list">
    <ul>
      <li>Find designers</li>
      <li>Inspiration</li>
      <li>Courses</li>
      <li>Jobs</li>
      <li>Go Pro</li>
    </ul>
  </div>
</template>

<script>
export default {

}
</script>

<style scoped>
@media only screen and (min-width: 601px) and (max-width: 900px) {
  .list>ul {
  display: none !important;
  
}
}
.list>ul {
  list-style: none;
  display: flex;
  gap: 32px;
  font-size: 15px;
  font-weight: 600;
}
.logo {
  height: 38px;
  width: 96px;
}
@media only screen and (max-width: 600px) {
  .list>ul {
  display:none
}

}
</style>

















