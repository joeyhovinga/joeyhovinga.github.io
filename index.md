<!DOCTYPE html>
<html>
<head>


</head>


<style>
#programs
{
  background-color:orange;
}

#Tabel1
{
  border: 1px solid black;
  padding: 0px;
  
}
tr:nth-child(odd)
{
  background-color: slateblue;
}la
tr:nth-child(even)
{
  background-color: slategray;

}


td:hover
{
background-color: fuchsia
}

th:hover
{
background-color: fuchsia
}

.col1 {
  float: left;
  width: 300px;
}

.col2 {
  float: middle;
  width:250px;
  margin-left:600px;
}

.img1 {
  display: inline-block;
 width: 100px;
 margin-left: 50;
}

.img2 {
  display: inline-block;
  width:100px;
  margin-left:250px;
}

ul {
    list-style-type: vertical;
    margin: 10;
    padding: 5;
}

li a {
    display: block;
    width: 60px;
    background-color: #dddddd;
}

</style>   

<ul>
    <li><a href="#Top">Top</a></li>
    <li><a href="#Curriculum Vitae">Curriculum Vitae</a></li>
    <li><a href="#Hobby's">Hobby's</a></li>
    <li><a href="#ContactFormulier">ContactFormulier</a></li>
  </ul>

<body>
  <h1>Curriculum Vitae</h1>
<table id="Tabel1" border="1"> 
  <tr>
    <TR> 
      <th> Naam   </th> <td id="td"> Joey Anthony Hovinga </td> 
    </TR>
    <TR> 
      <th> Geslacht  </th> <td id="td"> Man </td> 
    </TR>
    <TR> 
      <th> Geboortedatum </th> <td id="td"> 21/09/1996 </td> 
    </TR>
    <TR> 
      <th> Woonplaats </th> <td id="td"> Leeuwarden </td> 
    </TR>
    <TR> 
      <th> Hobby's </th> <td id="td">  League of Legends en Electrische gitaar spelen </td>
     </TR>
    <TR> 
      <th> Vooropleiding </th> <td id="td">  Integrale Veiligheid te NHL Leeuwarden </td> 
    </TR>
  </tr>
</table>


<h1>Programmeertalen die ik ken</h1>


<table id="programs" border="1">
<TR> 
  <TH> html </TH> <TH> CSS </TH>
</TR>
<TR> 
  <td id="td"> <a href=https://en.wikipedia.org/wiki/HTML target="_blank"><img src="https://www.w3.org/html/logo/downloads/HTML5_Logo.svg" alt="html" width="100" height="100"> </a> 
</td> 
  <td id="td"> <a href=https://en.wikipedia.org/wiki/Cascading_Style_Sheets target=_"blank"><img src="https://cdn.freebiesupply.com/logos/large/2x/css-3-logo-svg-vector.svg" alt="css" width="100" height="100"> </a> </td> 
</TR>      
</table>

<h1> Hobby's </h1>
<div class="img1">
    <img src= "https://vignette.wikia.nocookie.net/yogscast/images/7/77/League_of_Legends_logo.png/revision/latest?cb=20160704002536" alt="LoL" style="width:100" height="100">
</div>
<div class="img2">
  <img src="https://upload.wikimedia.org/wikipedia/commons/0/01/Gibson_Les_Paul_54_Custom.jpg" alt="gibson" style="width:100" height="100"> 
</div>
</div>

<div class="col1">
  <div> League of Legends is een MOBA (multiplayer online battle arena). League of Legends kan enkel online gespeeld worden tegen andere menselijke spelers of bots (computer bestuurd). Hierbij worden de spelers, ook wel Summoners genoemd, in een team geplaatst. Er zijn in totaal twee teams die het tegen elkaar opnemen. Deze teams bestaan uit vijf of drie spelers per team. Ieder team heeft een Nexus (basis). Als deze eenmaal vernietigd is, heeft het team die zijn Nexus nog heeft gewonnen. De spelers verdienen door het spel heen gold (goudstukken). Dit is virtueel geld waarmee ze in de spelronde voorwerpen kunnen kopen. Van deze voorwerpen wordt de speler sterker </div>
</div>
<div class="col2">
  <div>Electrische gitaar is een gitaar die geen klankkast heeft maar geluid produceert met behulp van een luidspreker. De trillingen van de stalen snaren wordt opgepakt door electromagnetische opnemers (elementen) en wordt vie een kabel naar een versperket geleidt. Mijn favoriete soort electrische gitaar is de 'Gibson Les Paul'  </div> 
   </div>


<form>
   <h1>Contact Formulier</h1>

   <div class="container">
     <form action="/action_page.php">
       <label for="Naam">Naam</label>
       <input type="text" id="fname" name="Naam" placeholder="Naam...">
   
       <label for="lname">E-Mail</label>
       <input type="text" id="lname" name="E-Mail" placeholder="E-Mail...">
   
       <label for="Onderwerp">Onderwerp</label>
       <select id="Onderwerp" name="Onderwerp">
         <option value="Hobby's">Hobby's</option>
         <option value="Werk">Werk</option>
         <option value="Opleiding">Opleiding</option>
         <option value="Info">Info</option>
         <option value="Overig">Overig</option>
       </select>
   
       <label for="Bericht">Bericht</label>
       <textarea id="Bericht" name="Bericht" placeholder="Schrijf hier..." style="height:200px"></textarea>
   
       <input type="submit" value="Submit">
     </form>

    
</body>

</html>
