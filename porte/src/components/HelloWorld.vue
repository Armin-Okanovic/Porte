<template>
  <div class="hello">
    <h1>VELKOMMEN TIL MIN PORTFOLIO
 </h1>
  <h2 id="bullitpoint">
   
    HER FINDER DU HVEM JEG ER & MINE PROJEKTER
 </H2>
    <h1>{{ msg }}</h1>
    <div class="rounded">
    <img src="../assets/lv.jpg"> 
    </div>
   
    <h1>
Armin Okanovic      
    </h1>
   
   
    <h3>
      Mine Projekter 
      
    </h3>
    <h3>VIDEO/REDIGIERING</h3>
    <ul>
      <li><a href="https://www.youtube.com/watch?v=2TrPDs8GUD0" target="_blank" rel="noopener">CV VIDEO</a></li>
      <li><a href="https://youtu.be/xiaiFXE-rFA" target="_blank" rel="noopener">SHORT MOVIE</a></li>
    <li><a href="https://www.youtube.com/watch?v=nqNb4qBQlXc" target="_blank" rel="noopener">COMMERCIAL</a></li>
    <li><a href="https://youtu.be/gbzIRR6Gi9Qtarget=" target="_blank" rel="noopener">CARPORN</a></li>
    </ul>
    <h3>DOKUMENTER/ART</h3> 

    <ul>
      <li><a href="../files/CV-kopi.pdf" target="_blank" rel="noopener">CV</a></li>
      <li><a href="../files/Business Card_AO.pdf" target="_blank" rel="noopener">BUSINESS CARD</a></li>
      <li><a href="../files/sketch-pc.pdf" target="_blank" rel="noopener">SKETCH FOR PC</a></li>
      <li><a href="../files/sketch-mobile.pdf" target="_blank" rel="noopener">SKETCH FOR MOBILE</a></li>
      <li><a href="../files/mobile-site.pdf" target="_blank" rel="noopener">MOBILE SITE FOR MY BUSINESS</a></li>
      <li><a href="../files/mood board.pdf" target="_blank" rel="noopener">MOOD BOARD</a></li>
      <li><a href="../files/Style-Tile.pdf" target="_blank" rel="noopener">STYLE TILE</a></li>
    </ul>
    <h3>SOCIALE MEDIER</h3>
    <ul>
      <li><a href="https://www.linkedin.com/in/armin-okanovic-161457144/" target="_blank" rel="noopener">LINKEDIN</a></li>
      <li><a href="https://www.instagram.com/one.is.schwarz/" target="_blank" rel="noopener">INSTAGRAM PRIVAT</a></li>
      <li><a href="https://www.instagram.com/armin_okanovic/" target="_blank" rel="noopener">INSTAGRAM BUSINESS</a></li>
   
     </ul>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
#bullitpoint {
 
}
h2#bullitpoint::before  {
  content: "•";
  color: goldenrod
}
h2#bullitpoint::after  {
  content: "•";
  color: goldenrod
}
h3 {
  margin: 40px 0 0;
  font-size: 12px
    
}
h1{
  text-align: auto;
  
}
.rounded{
  //height: 100vh;
  width: 375px;
  margin: auto;
 
  clip-path: circle();
  display: flex;
  justify-content: center;
  align-items: center;
}
.rounded img{
  border-radius: 0%;
}

ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
 }
a {
  color: black
  
}
</style>

