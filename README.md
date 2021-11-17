# arquitetura-css-treino
Projeto simples para explorar os conceitos sobre a métodologia CSS BEM (Block-Element-Modifier).

#example

```
 <html lang="pt-br">
   <head>
     ...
     <title>XXXX</title>
     <description>Exemplo sobre métodologia BEM</description>
   </head>
   <body>
   
    <header class="cabecalho">
       
       <h1 class="cabecalho__titulo">Algum texto qualquer</h1>
       
       <nav class="cabecalho__menu">
          <ul class="cabecalho__menu-lista">
          
            <li class="cabecalho__menu-item">
              <a href="#" class="cabecalho__menu-link--emphasis">Home</a>
            </li>
            
            <li class="cabecalho__menu-item">
              <a href="#" class="cabecalho__menu-link">Page 1</a>
            </li>
            
            <li class="cabecalho__menu-item">
              <a href="#" class="cabecalho__menu-link">Page 2</a>
            </li>
          
          </ul>
       </nav>
    </header>
    
    ...
    
   </body>
 </html>
```

