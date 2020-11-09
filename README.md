# Netflix Logo 
<img src="https://www.rvtecnologia.com.br/wp-content/uploads/2014/11/Netflix-Logo.png" height="40px">

## Foram utilizados apenas HTML e CSS

### HTML
 - Foram utilizados uma div com classe logo
   - Dentro dela uma div com classe netflix e 3 spans vazios
 - E um h3 escrito Netflix


### CSS
  - No body utilizei a animação para criar um degradê de inicia que para na última cor, também utilzei display flex para deixar os elementos centralizados
  - Na classe Netflix foi utilizado o :before
    - No :before:
      - Foi utilizado para criar o efeito de curva nas letras, coloquei bottom 0 e position absolute, com radius na parte superir da div criando um efeito meio que "meio circulo", foi utilizado a mesma animação do body para acompanhar a cor e passar despercebido esse elemento
  - Utilizei o :nth-child em cada span e distribuindo as animações com o delay necessário para que haja uma sincronização entre elas
  - No h3 foi utilizado animação para deixar visivel após o término da animação dos spans e um transform scale para dar um efeito de pulo
  
  
  ## PREVIEW
  <img src="https://media.giphy.com/media/CiUm4gY4SZ4LQRvKiP/giphy.gif" width="350px">
  
       - 
