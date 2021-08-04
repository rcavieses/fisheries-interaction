<p id="start">En una lejana ciudad, hace mucho tiempo.. close…</p>

<h1>AGRADECIMIENTOS<sub>titles in CSS3</sub></h1>

<div id="titles"><div id="titlecontent">

  <p class="center">EPISODIO III<br>EL DOCTORADO CSS3</p>
  
  <p>En este trabajo de grado quiero agradecer a muchas personas, quienes me han apoyado de innumerables formas.</p>
  
  <p> Pues a lo largo del tiempo que ha durado el trabajo me he visto enfrentado a diferentes retos, académicos y familiares</p>
  
  <p> No hubiera culminado esta aventura sin el apoyo de las siguientes personas, quienes son mi familia, amigos y mentores</p>
  
  <p>Also, by mentioning "Star Wars", everyone will understand what I mean. And I'll receive several thousand more visits.</p>
  
  <p>The scrolling titles work well in Chrome, Safari and Firefox. Opera doesn't implement 3D transforms yet, but the text will scroll. IE users receive a blank page. A shame, but IE10 should support it.</p>
  
  <p>So how does it work? Well, it's fairly simple. We have an outer absolute DIV (#titles) which is rotated along the X-axis using perspective to give the impression of depth. The same DIV also has an :after psuedo-element which applies a linear gradient so the text appears to fade out.</p>
  
  <p>Inside, we have another absolutely-positioned DIV which contains the text (#titlecontent). The top is set to 100% to ensure it starts off-screen then uses CSS3 animation to move it upward over time. No JavaScript is required.</p>
  
  <p>You will probably need to adjust the movement amount and timing depending on the quantity of text you want to show. The 3D depth can also be tweaked in the #titles declaration.</p>
  
  <p>All the code is contained in this single HTML file…
  
  </p><p class="center">View the source, Luke!</p>
  
  <p>Sorry. Couldn't resist it.</p>
  
  <p>You're welcome to use this demonstration code in your own sites. Please link back to the original article at:</p>
  
  <p class="center"><a href="http://www.sitepoint.com/css3-starwars-scrolling-text/">sitepoint.com/<br>css3-starwars-scrolling-text/</a></p>
  
  <p>and give me a shout on Twitter <a href="https://twitter.com/craigbuckler">@craigbuckler</a> – I'd love to see how you use and abuse it!</p>
  
  <p>Finally, Han shot first and the original, unadulterated movies remain the best. Stop fiddling with them, George!</p>

</div></div>

<footer class='credit'>
  This is a fork of <a href='https://twitter.com/craigbuckler'>Craig Buckler</a>´s <a href='http://blogs.sitepointstatic.com/examples/tech/css3-starwars/index.html'>demo</a>. From 2012 on <a href='http://www.sitepoint.com/css3-starwars-scrolling-text/'>sitepoint.com</a>
</footer>
