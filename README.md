# desafio-09-matias-igenes
SEGUNDA ENTREGA DEL RPYECTO FINAL

Agregue grids y nuevas clases

.contenedor {
    background-color: #9b9b9b;
    display: grid;
    grid-template-areas: "header header header"
    "nav nav nav"
    "main main main"
    "footer footer footer";
  }
  
  .contenedor div {
    color: #000000;
    
  }
  /* fondo del body */
  body {
    margin: 5px;
  }
  .item-1 {
    grid-area: header;
  }
  
  .item-2 {
    grid-area: nav;
    padding: 10px;
    
  }
  
  .item-3 {
    grid-area: main;
    padding: 10px;
  }
  
  .item-4 {
    grid-area: footer; 
    padding: 10px; 
  }