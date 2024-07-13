<template>
    <div class="navbar">
  
  <div class="logo">
  
  </div>
  
  <div class="user-info">
      <div>
          <img src="" alt="">    
      </div>
      <div>
          <img src="" alt="">
      </div>
      <div>
          <button class="btn2">Adan Schwartz</button>
      </div>
  </div>
  
  </div>
  
  <div class="main-wrapper">
  <div class="sidebar">
      <button class="sidebar-btn">Dashboard</button>
      <button class="sidebar-btn">Menu</button>
      <button class="sidebar-btn">Visualizar</button>
      <button class="sidebar-btn">Empleados</button>
      <button class="sidebar-btn">Metodos de pago</button>
      <button class="sidebar-btn">Proveedores</button>
      <button class="sidebar-btn">Inventario</button>
  </div>
  
  
  <div class="container">
      <div class="superior">
          <h1>Inventario</h1>
          <button>Agregar item</button>
      </div>
      <hr class="separator">
      <div class="lista">
          <div class="item">
              <div class="item-inicio">
                  <h3>Tomates cherry(100gr)</h3>
                  <p>tometes enlatadps cherry</p>
              </div>
              <div class="item-medio">
                  <h2>Producto</h2>
              </div>
              <div class="item-centro">
                  <h2>192</h2>
                  <p>unidades</p>
              </div>
          </div>
          <div class="item">
              <div class="item-inicio">
                  <h3>Tomates cherry(100gr)</h3>
                  <p>tometes enlatadps cherry</p>
              </div>
              <div class="item-medio">
                  <h2>Producto</h2>
              </div>
              <div class="item-centro">
                  <h2>192</h2>
                  <p>unidades</p>
              </div>
          </div>
          <div class="item">
              <div class="item-inicio">
                  <h3>Tomates cherry(100gr)</h3>
                  <p>tometes enlatadps cherry</p>
              </div>
              <div class="item-medio">
                  <h2>Producto</h2>
              </div>
              <div class="item-centro">
                  <h2>192</h2>
                  <p>unidades</p>
              </div>
          </div>
      </div>
  </div>
  
  </div>
  </template>
  
  <script>
  
  </script>
  
  <!-- Add "scoped" attribute to limit CSS to this component only -->
  <style>
  body {
      padding: 0;
      margin: 0;
      background-color: #141313;
      height: 100vh; /* Asegura que el body ocupe toda la altura de la ventana */
  }
  
  .main-wrapper {
      display: flex;
      height: calc(100vh - 50px); /* Resta la altura del navbar */
  }
  
  .navbar {
      display: flex;
      background-color: #000000;
      height: 50px;
  }
  
  .logo {
      width: 20%;
  }
  
  .user-info {
      width: auto;
      display: flex;
      align-items: center;
      margin-left: auto;
      gap: 10px;
      padding-right: 20px;
  }
  
  .user-info h1 {
      color: #8C9094;
  }
  
  .user-info img {
      color: aliceblue;
  }
  
  .btn1 {
      height: 30px;
  }
  
  .btn2 {
      border-radius: 5px;
      border: none;
      height: 35px;
      padding: 0 20px;
  }
  
  .sidebar {
      background-color: #2C2E3A;
      display: flex;
      flex-direction: column;
      width: 17%;
      height: 100%; /* Cambiado para ocupar toda la altura disponible */
  }
  
  .sidebar-btn {
      background-color: transparent;
      border: none;
      width: 100%;
      text-align: left;
      padding: 13px 60px;
      color: #8C9094;
      font-size: 15px;
  }
  
  .container {
      width: 83%;
      display: flex;
      flex-direction: column; /* Cambia a columna para apilar los elementos */
      height: 100%;
  }
  
  .superior {
      display: flex;
      width: 100%;
      height: 15%;
      align-items: center;
      justify-content: space-between; /* Distribuye los elementos horizontalmente */
      padding: 0 30px;
      box-sizing: border-box; /* Incluye el padding en el ancho total */
  }
  .superior h1{
      color: white;
      font-weight: bold;
      font-size: 50px;
      
  }
  .superior button{
      background-color: #FF7A00;
      border: none;
      border-radius: 20px;
      height: 30px;
      padding: 0 60px;
      margin-left: auto;
      color: white;
      font-weight: bold;
  }
  .separator {
      width: 95%;
      height: 2px;
      background-color: #808080;
      border: none;
      margin: 10px auto;
  }
  .lista {
      display: flex;
      flex-grow: 1;
      flex-direction: column;
      align-items: center; /* Centra los items horizontalmente */
  }
  
  .item {
      background-color: #D9D9D9;
      display: flex;
      width: 90%;
      height: 15%;
      margin: 5px 0; /* Añade algo de espacio vertical entre items */
      
  }
  .item-inicio{
      width: 50%;
  }
  .item-inicio h3 {
      padding-left: 150px;
  }
  .item-inicio p {
      padding-left: 150px;
      color: #717171;
      font-weight: bold;
      margin-top: -10px;
  }
  .item-medio{
      width: 20%;
      color: #717171;
      text-align: center;
  }
  .item-centro{
      width: 30%; 
      text-align: right;
  }
  .item-centro h2 {
      font-size: 30px ;
      padding-right: 40px;
      margin-top: 10px;
  }
  .item-centro p {
      color: #717171;
      font-weight: bold;
      margin-top: -20px;
      padding-right: 30px;
  }
  </style>