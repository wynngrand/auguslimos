<script>
	import data from '../../data/home.json';
</script>
<div class="row mt-5 slim">
<div class="col-md-6 p-3 p-md-5 mt-5">
<h1><strong><a href="/" class="text-dark">{data.title}</a></strong></h1>
<h2><strong>{data.desc}</strong></h2>
<a href={data.btnlink} class="btn btn-dark btn-lg">{data.btn}</a>
</div>
<div class="col-md-6 p-3 p-md-5">
<img class="img-fluid" width="600" height="300" alt={data.title} src={data.image}/>
</div>
	<div class="col-md-12 p-3 p-md-5">
	<p>{data.text1}<br/>{data.text2}<br/>{data.text3}<br/>{data.text4}<br/>{data.text5}</p>
	<p>{data.text6}</p>
	<p>{data.text7}</p>
	</div>
</div>
