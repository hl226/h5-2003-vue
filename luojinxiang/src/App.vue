<template>
  <div id="app">
    <router-view></router-view>
  </div>
</template>

<style>
  #app{
    height: 100%;
  }
  html,body,ul,li,ol,dl,dd,dt,p,h1,h2,h3,h4,h5,h6,form,fieldset,legend,img,input {
      margin: 0;
      padding: 0
  }
  html,body{
    width: 100%;
    height: 100%;
  }
  body {
    font: 12px Arial,Helvetica,sans-serif;
  }
  ul,ol,li {
      list-style: none;
  }
  b,strong {
      font-weight: normal;
  }
  em,i {
      font-style: normal;
  }
  a,u {
      text-decoration: none;
  }
  h1,h2,h3,h4,h5,h6 {
      font-size: 16px;
      font-weight: normal;
  }
  input,button {
      outline: none;
      border: 0;
  }
  img {
      display: block;
      border: 0;
  }
</style>
