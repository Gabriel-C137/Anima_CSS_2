# Anima_CSS_1
Animação Feita por mim utilizando apenas CSS e HTML, representa o magnetismo.<br>
Feito pelo [|Codepen](https://codepen.io/sawwzozo-the-vuer/pen/mdYepVy)
<br>
<div align="center">
<img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Smilies/Nerd%20Face.png" alt="Nerd Face" width="100" height="100" /></div>
--------------------------------------------------------------------------------------------------------------------------------------------------------------
<div align="center"> GABRIEL CAMARA DE OLIVEIRA </div>
--------------------------------------------------------------------------------------------------------------------------------------------------------------
<div align="center">
<a href="https://www.instagram.com/gabriel_c137/">Siga-me no Instagram</a>    <br>and<br>  <a href="https://github.com/Gabriel-C137">Acompanhe o meu perfil para ver a evolução</a>
</div>
--------------------------------------------------------------------------------------------------------------------------------------------------------------
--------------------------------------------------------------------------------------------------------------------------------------------------------------

##  🖇️ Colaboração:

* Professor Márcio - Fatec Franca
* W3Schools.com.br - Site de Ensino sobre Programação [w3School](https://www.w3schools.com/html/default.asp)
* Gustavo Guanabra - Curso em Vídeo [Acesse aqui](https://www.cursoemvideo.com/curso/curso-html5-e-css3-modulo-2-de-5-40-horas/)
* Canal dpw - Youtube.com.br [Acesse aqui](https://www.youtube.com/@dpwoficial)

<br>

### 📋 Pré-requisitos:

Esse também não é nessesário nenhuma pré-instalação para a execução/vizualização desse projeto, basta um navegador de internet (como Google Chrome, Mozilla 
Firefox e/ou Microsoft Edge)
<hr>
<br>

<div align="center">Arma de stormtrooper atirando</div>

![17ee0623-2ebb-40fb-9ce6-c3350c7e3f5f](https://github.com/Gabriel-C137/Anima_CSS_2/assets/91295561/db4cd743-d45b-421b-ab01-6454bc1dd029)


### Código HTML_5 do meu projeto

```
<div class="gun-holder">
  <div class="gun-box1"></div>
  <div class="gun-box2"></div>
  <div class="gun-box3"></div>
  <div class="gun-box4"></div>
</div>

<div class="gun">
  <div class="gun-body"></div>
  <div class="bullet"></div>
</div>
```

### Código CSS_3 do meu projeto

```
body {
  display: flex;
  justify-content: center;
  align-items: center;
  height: 100vh;
  background-color: #f0f0f0;
}

.gun {
  position: relative;
  width: 100px;
  height: 60px;
}

.gun-body {
  position: absolute;
  width: 80px;
  height: 35px;
  background-color: #333;
  border-radius: 5px;
  transform: translateX(-5px);
}
.gun-holder {
  width: 30px;
  height: 40px;
  background-color: #333;
  border-radius: 5px;
}
.gun-box1 {
  width: 30px;
  height: 40px;
  padding: 2px;
  background-color: #333;
  border-radius: 5px;
  transform: translateX(-5px);
}

.gun-box2 {
  width: 30px;
  height: 40px;
  background-color: #333;
  border-radius: 5px;
  transform: translateY(-10px);
}

.gun-box3 {
  width: 5px;
  height: 20px;
  background-color: #333;
  border-radius: 5px;
  transform: translateY(-100px);
}

.gun-box4 {
  position: absolute;
  width: 20px;
  height: 20px;
  padding-left: 100px;
  background-color: #333;
  border-radius: 5px;
  transform: translateY(-112px);
}

.bullet {
  position: absolute;
  top: 7px;
  left: 80px;
  width: 41px;
  height: 10px;
  background-color: #ff0000;
  animation: shoot 2s infinite;
  animation-delay: 2s;
  opacity: 0;
}
.trigger {
  transform: translateX(45px);
  background-color: transparent;
  box-shadow: 1px 1px 1px 1px #333;
  width: 50px;
  height: 40px;
  border-radius: 50%;
}

@keyframes shoot {
  0% {
    left: 90px;
    opacity: 1;
  }
  100% {
    left: calc(100% + 400px);
    opacity: 0;
  }
}
```
<br>
<hr>
<div align="center">...FIM...</div>
