<!doctype html>
<html>
<head>
<meta charset="utf-8">
<title>Ejercicios JS</title>

<script type="text/javascript">
function MM_openBrWindow(theURL,winName,features) { //v2.0
  window.open(theURL,winName,features);
}
function MM_popupMsg(msg) { //v1.0
  alert(msg);
}
function MM_showHideLayers() { //v9.0
  var i,p,v,obj,args=MM_showHideLayers.arguments;
  for (i=0; i<(args.length-2); i+=3) 
  with (document) if (getElementById && ((obj=getElementById(args[i]))!=null)) { v=args[i+2];
    if (obj.style) { obj=obj.style; v=(v=='show')?'visible':(v=='hide')?'hidden':v; }
    obj.visibility=v; }
}
</script>

<style type="text/css">
#apDiv1 {
	position: absolute;
	width: 459px;
	height: 303px;
	z-index: 1;
	left: 167px;
	top: 131px;
	visibility: hidden;
}
</style>

</head>

<body onLoad="MM_popupMsg('Este mensaje aparecerá al cargar la página web.')">
<p>Abrir archivo en ventana con propiedades:</p>

<p><a href="#" onClick="https://jotform.co/81844214464861">hipervínculo</a></p>


<p><a class="nav-link" id"a" href="../../pagina web stardust/encuesta.html">hola<span class="sr-only"></span></a>
  </li>
  
  
</p>

<p><a class="nav-link" id"a" href="https://jotform.co/81844214464861">hola2<span class="sr-only"></span></a>
  </li>
  
  
</p>
<p>&nbsp;</p>

<p onClick="MM_popupMsg('Este es un mensaje emergente que aparecerá al darle click al hipervínculo.')"><a href="#">
<img src="ima/ima2.jpg" width="105" height="70" onMouseOver="MM_showHideLayers('apDiv1','','show')" onMouseOut="MM_showHideLayers('apDiv1','','hide')"></a></p>

<div id="apDiv1"><img src="ima/ima2.jpg" width="456" height="304"></div>

</body>
</html>

