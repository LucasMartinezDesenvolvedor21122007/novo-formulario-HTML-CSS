<!DOCTYPE html>
<html lang="en">
</head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" type="index.css" href="index.css" media="screen"> 
<title>Cadastro</title>
<head>
<body>

<div class="campo">
    <h1 id="titulo">Cadastro De DEVs</h1>
    <p id="subtitulo">Complete suas informações</p>
    <br>
</div class="campo">

<form>
  <fieldset class="grupo">
        <div class="campo">
           <label for="nome"><strong>Nome</strong></label>
           <input type="text" name="nome" id="nome" required>
        </div class="campo">

        <div class="campo">
          <label for="sobrenome"><strong>Sobrenome</strong></label>
          <input type="text" name="Sobrenome" id="Sobrenome" required>
        </div class="campo">
  </fieldset class="grupo">

  <div class="campo">
    <label for="email">Email</label>
    <input type="email" name="email" id="email" required>
  </div class="campo">


<div class="campo">
    <label>De qual lado da aplicação você desenvolve</label>
    <br>
    <label>
        <input type="radio" name="Devweb" value="Front-End">Front-End
        <br>
        <input type="radio" name="devweb" value="Back-End">Back-End
        <br>
        <input type="radio" name="devweb" value="Full-Stack" checked>Full-Stack
    </label>
</div class="campo">

<div class="campo">
   <label>Senioridade</label>
   <select id="senioridade">
    <option>Junior</option>
    <option>Pleno</option>
    <option>Sênior</option>
    <option selected disabled value="">Escolha</option>
   </select>
</div class="campo">

<fieldset>
    <div id="checkbox">
        <label><strong>selecione as tecnologias que utiliza:</label><br><br>
        <input type="checkbox" id="tecnologia1" name="tecnologia1" value="HTML">
        <label for="tecnologia1">HTML</label>
        <input type="checkbox" id="tecnologia2" name="tecnologia2" value="CSS">
        <label for="tecnologia2">CSS</label>
        <input type="checkbox" id="tecnologia3" name="tecnologia3" value="Javascript">
        <label for="tecnologia3">Javascript</label>
        <input type="checkbox" id="tecnologia4" name="tecnologia4" value="PHP">
        <label for="tecnologia4">PHP</label>
        <input type="checkbox" id="tecnologia5" name="tecnologia5" value="C#">
        <label for="tecnologia5">C#</label>
        <input type="checkbox" id="tecnologia6" name="tecnologia6" value="Python">
        <label for="tecnologia6">Python</label>
        <input type="checkbox" id="tecnologia7" name="tecnologia7" value="C++">
        <label for="tecnologia7">C++</label>
    </div class="campo">
</fieldset>

<div class="campo">
    <br>
    <label>Conte para nós a sua experiência</label>
    <textarea row="6" style="width: 25em" id="experiência" name="experiência"></textarea>
</div class="campo">

<button type="submit" class="botão">Concluido</button>

</form>
</body>
</head>

*{
   margin:0;
   padding:0; 
}

#titulo{
   font-family: sans-serif;
   color: #380b61;;
   margin-left: 7%;
}

#subtitulo{
    font-family: sans-serif;
    color: #380b61;;
    margin-left: 10%;
}

fieldset{
    border: 0;
}

body{
    background-color: #380b61;
    font-family: sans-serif;
    font: size 1em;
    color:#380b61;
    margin-left: 35%;
    margin-top: 2%;
    justify-content: center;
}

input, select, textarea, button{
    border-radius: 5px;
}

.campo{
   margin-bottom:1em ; 
}

.campo label{
    margin-bottom: 0.2em;
    color:#380b61;
    display: block;
}

fieldset.grupo.campo{
   float:left ; 
   margin-right:1em ;
}

.campo input[type="text"], .campo input[type="email"], .campo select, .campo textarea{
    padding: 0.2em;
    border: 1px solid #380b61;
    box-shadow: 2px 2px 2px #380b61;
    display: block;
}

.campo select option{
    padding-right:2em;
}

.campo input:focus, .campo select:focus, .campo textarea:focus{
    background-color: rgb(56, 11, 97);
}

.botão {
    font-size: 1.2em;
    background-color: #380b61;
    border: 0;
    margin-bottom: 1em;
    color: #380b61;
    padding: 0.2em 0.7em;
    box-shadow: 1px, 1px, 1px;
    text-shadow: #000000 1px,1px, 1px;
    position: absolute;
    top: 90%;
    margin-right: -50%;
    transform:translate(-50%, -50%)
}

.botão:houver{
    background: #59429d;
    box-shadow:inset 2px 2px 2px rgba(0,0,0,0.2);
    text-shadow: none;
}

#check {
    display:inline-block;
}
