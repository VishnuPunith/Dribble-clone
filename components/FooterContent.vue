<template>
    
 <div class="foot_con">
        <ul>
          <li>Find designers</li>
          <li>Hire talent</li>
          <li>Inspiration</li>
          <li>Advertising</li>
          <li>Blog</li>
          <li>About</li>
          <li>Careers</li>
          <li>Support</li>
        </ul>
      </div>
    
</template>


<style>
@media only screen and (min-width: 601px) and (max-width: 900px) {
  .foot_con>ul{
    gap: 4px !important;
  }
}
@media only screen and (max-width: 600px) {
  .foot_con>ul {
  display: flex !important;
  flex-direction: column;
  gap: 17px !important;

}
.foot_text{
  display:flex;
  gap: 21px;
}
}
.foot_con>ul {
  list-style: none;
  display: flex;
  gap: 32px;
  font-size: 15px;
  font-weight: 600;
  cursor: pointer;

}
.foot_text {
  display: flex;
  justify-content: space-around;
  margin-top: 65px;
}
.logo {
  height: 38px;
  width: 96px;
}
</style>