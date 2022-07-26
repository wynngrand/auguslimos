<script>
	import data from '../../data/home.json';
</script>
<div class="row slim" id="fleet">
<div class="col-md-12 p-3 p-md-5 text-center">
<h3>{data.fleet}</h3>
<p>{data.fleetdesc}</p>
</div>

<div class="col-md-4 p-3">
<div class="card p-1">
<h3 class="card header p-1 black text-white text-center"><a href="/" class="text-white">{data.car1}</a></h3>
<img class="img-fluid" alt={data.car1} src={data.car1img}/>
<div class="card-content p-3">
<p>{data.car1text1} <br/> {data.car1text2}</p>
<div class="card-footer row">
<div class="col-md-5 col-6">
<p>{data.carstart}</p>
</div>
<div class="col-md-5 col-6">
<p>{data.car1price}</p>
</div>
<a href={data.carlink} class="btn col-md-2">
<svg xmlns="http://www.w3.org/2000/svg" width="26" height="26" fill="currentColor" class="bi bi-arrow-right-circle-fill" viewBox="0 0 16 16">
  <path d="M8 0a8 8 0 1 1 0 16A8 8 0 0 1 8 0zM4.5 7.5a.5.5 0 0 0 0 1h5.793l-2.147 2.146a.5.5 0 0 0 .708.708l3-3a.5.5 0 0 0 0-.708l-3-3a.5.5 0 1 0-.708.708L10.293 7.5H4.5z"/><title>{data.title}</title>
</svg>
 </a>
</div>
</div>
</div>
</div>

<div class="col-md-4 p-3">
<div class="card p-1">
<h3 class="card header p-1 black text-white text-center"><a href="/" class="text-white">{data.car2}</a></h3>
<img class="img-fluid" alt={data.car2} src={data.car2img}/>
<div class="card-content p-3">
<p>{data.car2text1} <br/> {data.car2text2}</p>
<div class="card-footer row">
<div class="col-md-5 col-6">
<p>{data.carstart}</p>
</div>
<div class="col-md-5 col-6">
<p>{data.car2price}</p>
</div>
<a href={data.carlink} class="btn col-md-2">
<svg xmlns="http://www.w3.org/2000/svg" width="26" height="26" fill="currentColor" class="bi bi-arrow-right-circle-fill" viewBox="0 0 16 16">
  <path d="M8 0a8 8 0 1 1 0 16A8 8 0 0 1 8 0zM4.5 7.5a.5.5 0 0 0 0 1h5.793l-2.147 2.146a.5.5 0 0 0 .708.708l3-3a.5.5 0 0 0 0-.708l-3-3a.5.5 0 1 0-.708.708L10.293 7.5H4.5z"/>
<title>{data.title}</title></svg>
 </a>
</div>
</div>
</div>
</div>

<div class="col-md-4 p-3">
<div class="card p-1">
<h3 class="card header p-1 black text-white text-center"><a href="/" class="text-white">{data.car3}</a></h3>
<img class="img-fluid" alt={data.car3} src={data.car3img}/>
<div class="card-content p-3">
<p>{data.car3text1} <br/> {data.car3text2}</p>
<div class="card-footer row">
<div class="col-md-5 col-6">
<p>{data.carstart}</p>
</div>
<div class="col-md-5 col-6">
<p>{data.car3price}</p>
</div>
<a href={data.carlink} class="btn col-md-2">
<svg xmlns="http://www.w3.org/2000/svg" width="26" height="26" fill="currentColor" class="bi bi-arrow-right-circle-fill" viewBox="0 0 16 16">
  <path d="M8 0a8 8 0 1 1 0 16A8 8 0 0 1 8 0zM4.5 7.5a.5.5 0 0 0 0 1h5.793l-2.147 2.146a.5.5 0 0 0 .708.708l3-3a.5.5 0 0 0 0-.708l-3-3a.5.5 0 1 0-.708.708L10.293 7.5H4.5z"/>
<title>{data.title}</title></svg>
 </a>
</div>
</div>
</div>
</div>

<div class="col-md-4 p-3">
<div class="card p-1">
<h3 class="card header p-1 black text-white text-center"><a href="/" class="text-white">{data.car4}</a></h3>
<img class="img-fluid" alt={data.car4} src={data.car4img}/>
<div class="card-content p-3">
<p>{data.car4text1} <br/> {data.car4text2}</p>
<div class="card-footer row">
<div class="col-md-5 col-6">
<p>{data.carstart}</p>
</div>
<div class="col-md-5 col-6">
<p>{data.car4price}</p>
</div>
<a href={data.carlink} class="btn col-md-2">
<svg xmlns="http://www.w3.org/2000/svg" width="26" height="26" fill="currentColor" class="bi bi-arrow-right-circle-fill" viewBox="0 0 16 16">
  <path d="M8 0a8 8 0 1 1 0 16A8 8 0 0 1 8 0zM4.5 7.5a.5.5 0 0 0 0 1h5.793l-2.147 2.146a.5.5 0 0 0 .708.708l3-3a.5.5 0 0 0 0-.708l-3-3a.5.5 0 1 0-.708.708L10.293 7.5H4.5z"/>
<title>{data.title}</title></svg>
 </a>
</div>
</div>
</div>
</div>

<div class="col-md-4 p-3">
<div class="card p-1">
<h3 class="card header p-1 black text-white text-center"><a href="/" class="text-white">{data.car5}</a></h3>
<img class="img-fluid" alt={data.car5} src={data.car5img}/>
<div class="card-content p-3">
<p>{data.car5text1} <br/> {data.car5text2}</p>
<div class="card-footer row">
<div class="col-md-5 col-6">
<p>{data.carstart}</p>
</div>
<div class="col-md-5 col-6">
<p>{data.car5price}</p>
</div>
<a href={data.carlink} class="btn col-md-2">
<svg xmlns="http://www.w3.org/2000/svg" width="26" height="26" fill="currentColor" class="bi bi-arrow-right-circle-fill" viewBox="0 0 16 16">
  <path d="M8 0a8 8 0 1 1 0 16A8 8 0 0 1 8 0zM4.5 7.5a.5.5 0 0 0 0 1h5.793l-2.147 2.146a.5.5 0 0 0 .708.708l3-3a.5.5 0 0 0 0-.708l-3-3a.5.5 0 1 0-.708.708L10.293 7.5H4.5z"/>
<title>{data.title}</title></svg>
 </a>
</div>
</div>
</div>
</div>

<div class="col-md-4 p-3">
<div class="card p-1">
<h3 class="card header p-1 black text-white text-center"><a href="/" class="text-white">{data.car6}</a></h3>
<img class="img-fluid" alt={data.car6} src={data.car6img}/>
<div class="card-content p-3">
<p>{data.car6text1} <br/> {data.car6text2}</p>
<div class="card-footer row">
<div class="col-md-5 col-6">
<p>{data.carstart}</p>
</div>
<div class="col-md-5 col-6">
<p>{data.car6price}</p>
</div>
<a href={data.carlink} class="btn col-md-2">
<svg xmlns="http://www.w3.org/2000/svg" width="26" height="26" fill="currentColor" class="bi bi-arrow-right-circle-fill" viewBox="0 0 16 16">
  <path d="M8 0a8 8 0 1 1 0 16A8 8 0 0 1 8 0zM4.5 7.5a.5.5 0 0 0 0 1h5.793l-2.147 2.146a.5.5 0 0 0 .708.708l3-3a.5.5 0 0 0 0-.708l-3-3a.5.5 0 1 0-.708.708L10.293 7.5H4.5z"/>
<title>{data.title}</title></svg>
 </a>
</div>
</div>
</div>
</div>

</div>


