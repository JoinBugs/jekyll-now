---
layout: page
title: Algo Cursi sobre mi
permalink: /me/
---

<style>
#tecs
{
    border : 1px solid rgba( 0, 0, 0, .3 );
    padding : 30px;
    border-radius : 3px;
    box-shadow : 0px 0px 5px rgba( 0, 100, 250, .8 );
}

#tecs span
{
  display: inline-block;
  margin : 18px;
  transition : all .6s ease;
  cursor : pointer;
}

#tecs span:hover
{
  box-shadow : 5px 5px 3px rgba( 0, 0, 0, .3 );
  border-radius : 2px;
  transform : rotate( 1turn );
}

#tblTecs tr td:first-child
{
  border-radius : 1px;
  position: relative;
  display: inline-block;
  width : 350px;
  border-top : none;
  padding : 10px;
  box-shadow: 0px 0px 5px rgba( 0, 90, 200, .8 ) inset;
  border : 1px solid rgba( 0, 90, 200, .8 );
  margin : 2px;
  cursor : pointer;
  transition : all .8s ease;
}

#tblTecs tr td:first-child:hover
{
  background-color : rgba( 0, 90, 200, .8 );
  color : white;
}

#tblTecs tr td
{
  padding : 0px 8px;
}

#tblTecs tr td.empty, #tblTecs tr td.empty:hover
{
  cursor : inherit;
  border : none;
  box-shadow: none;
  background-color : initial;
}

#contentDom
{
  box-shadow : 0px 0px 1px rgba( 0, 0, 0, .5 ) inset;
  padding : 4px;
}

#contentDom .dom-block
{
  margin : 0 2px;
  display: inline-block;
  padding : 6px;
}

#contentDom .dom:first-child .dom-block, .dom-bas
{
  border : 1px solid rgba( 200, 90, 0, .7 );
  box-shadow : 0px 0px 2px rgba( 200, 90, 0, .7 ) inset;
  cursor : pointer;
  transition : all .7s ease;
}

#contentDom .dom:nth-last-child(2) .dom-block, .dom-med
{
  border : 1px solid rgba( 0, 200, 90, .7 );
  box-shadow : 0px 0px 2px rgba( 0, 200, 90, .7 ) inset;
  cursor : pointer;
  transition : all .7s ease;
}

#contentDom .dom:last-child .dom-block, .dom-ava
{
  border : 1px solid rgba( 0, 90, 255, .7 );
  box-shadow : 0px 0px 2px rgba( 0, 90, 255, .7 ) inset;
  cursor : pointer;
  transition : all .7s ease;
}

/*Hover*/
#contentDom .dom:first-child .dom-block:hover, .dom-bas:hover
{
  box-shadow : 0px 0px 20px rgba( 200, 90, 0, .7 ) inset;
}

#contentDom .dom:nth-last-child(2) .dom-block:hover, .dom-med:hover
{
  box-shadow : 0px 0px 20px rgba( 0, 200, 90, .7 ) inset;
}

#contentDom .dom:last-child .dom-block:hover, .dom-ava:hover
{
  box-shadow : 0px 0px 20px rgba( 0, 90, 255, .7 ) inset;
}
</style>

__*I am an apassioned for the web technologies, like HTML 5, CSS3 but in a special case JavaScript, i love the frameworks because i think that get the best of you.*__


### Tecnologias con las que actualmente trabajo
<section id="tecs">
    <span title="click para ver mis proyectos en HTML5"><i style="font-size : 5em;color : rgb(234, 61, 19);" class="fa fa-html5" aria-hidden="true"></i></span>
    <span title="Click para ver mis proyectos en JavaScript"><i style="font-size : 5em;color : rgb(245, 174, 9);" class="icon-javascript"></i></span>
    <span title="Click para ver mis proyectos en CSS"><i style="font-size : 5em;color : rgb(9, 178, 245);" class="fa fa-css3" aria-hidden="true"></i></span>
    <span title="Click para ver mis proyectos en Github"><i style="font-size : 5em;color : rgb(72, 65, 63);" class="fa fa-github" aria-hidden="true"></i></span>
    <span title="Click para ver mis proyectos en Git"><i style="font-size : 5em;color : rgb(234, 61, 19);" class="fa fa-git" aria-hidden="true"></i></span>
    <span title="Click para ver mis proyectos en Laravel5"><i style="font-size : 5em;color : rgb(234, 61, 19);" class="icon-laravel"></i></span>
    <span title="Click para ver mis proyectos en Java"><i style="font-size : 5em;color : rgb(83, 131, 222);" class="icon-java"></i></span>
    <span title="Click para ver mis proyectos en Python"><i style="font-size : 5em;color : rgb(25, 148, 35);" class="icon-python"></i></span>
    <span title="Click para ver mis proyectos en MySQL"><i style="font-size : 5em;color : rgb(19, 163, 234);" class="icon-mysql"></i></span>
    <span title="Click para ver mis proyectos en C#"><i style="font-size : 5em;color : rgb(54, 132, 23);" class="icon-csharp"></i></span>
</section>
---

### He aquí un poquito de lo que conosco
<table id="tblTecs">
    <tbody>
        <tr><td>Sistemas Operativos</td><td class="dom-med">Windows</td><td class="dom-bas">GNU-Linux/Deepin</td></tr>
        <tr><td>Ofimática nivel medio</td><td class="dom-med">Word</td><td class="dom-med">PowerPoint</td> <td class="dom-med">Excel</td></tr>
        <tr><td>Programación nivel avanzado</td><td class="dom-ava">JavaScript</td></tr>
        <tr><td>Programación nivel medio</td><td class="dom-med">Python</td><td class="dom-med">C#</td><td class="dom-med">Java</td><td class="dom-bas">Android</td></tr>
        <tr><td>Conocimiento en Tecnologías</td><td class="dom-ava">HTML5</td><td class="dom-med">CSS3</td><td class="dom-ava">Ajax</td><td class="dom-ava">DOM</td><td class="dom-ava">JSON</td><td class="dom-med">WebServices</td></tr>
        <tr><td class="empty"></td><td class="dom-med">ASP.NET</td><td class="dom-med">Windows Form</td><td class="dom-bas">Django</td><td class="dom-bas">JSP</td><td class="dom-med">MySQL</td><td class="dom-ava">BATCH</td></tr>
        <tr><td>Arquitecturas o Estilos de Arquitectura</td><td class="dom-ava">MVC</td><td class="dom-ava">DAO</td><td class="dom-med">REST</td><td class="dom-med">Híbridos</td></tr>
        <tr><td>Herramientas</td><td class="dom-med">Git</td><td class="dom-med">Mockup Builder</td></tr>
        <tr><td>Nivel de inglés</td><td class="dom-med">Intermedio</td></tr>
    </tbody>
</table>

#### Dominio
<div id="contentDom">
    <div class="dom"> <span class="dom-block"></span> <span class="dom-text">Basico</span></div>
    <div class="dom"> <span class="dom-block"></span> <span class="dom-text">Intermedio</span></div>
    <div class="dom"> <span class="dom-block"></span> <span class="dom-text">Avanzado</span></div>
</div>

---
### Aqui algunos de mis logros
[Microsoft Certified Professional][1]{:target="_blank"}  

---

### Contactame

<form action="https://formspree.io/buggerdeveloper@gmail.com"
      method="POST">
    <input class="form-control" type="text" name="name" placeholder="Aqui tu nombre, porfavor" > <br/>
    <input class="form-control"  type="email" name="_replyto" placeholder="Seria Genial, Si pudieras regalarme tu email aqui"> <br/>
    <label for="asunto">  <strong> En que puedo ayudarte? </strong> </label>
    <textarea placeholder="Adelante, porfavor comentame..."  class="form-control" name="asunto" id="asunto" cols="30" rows="10"></textarea> <br/>
    <input class="btn btn-info"  type="submit" value="Enviar">
</form>

[1]: /certificate.pdf