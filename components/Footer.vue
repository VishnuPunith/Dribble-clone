<template>

<div class = "footer_demo">
        <div class = "left_foot">
          <ul>
          <li>© 2024 Dribbble</li>
          <li>Terms</li>
          <li>Privacy</li>
          <li>Cookies</li>
        </ul>
        </div>
        <div class = "right_foot">
          <ul>
          <li>Jobs</li>
          <li>Designers</li>
          <li>Freelancers</li>
          <li>Tags</li>
          <li>Places</li>
          <li>Resources</li>
        </ul>
        </div>
      </div>
</template>

<style>
.footer_demo{
  display: flex;
  justify-content:space-between;
  padding: 76px;
}
.left_foot>ul{
  display: flex;
    justify-content: center;
    gap: 4pc;
    list-style: none;
    font-size: 100%;
    color: #6e6d7a;
    margin-left: -42px;
    font-weight: 400;
}
.right_foot>ul{
  display: flex;
    justify-content: center;
    gap: 40px;
    list-style: none;
    font-size: 100%;
    color: #6e6d7a;
    font-weight: 400;

}
</style>