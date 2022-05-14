# termux-dekstop
this is a desktop termux application that looks like a pc, has a light capacity and very good visuals
you can install it via your termux
by typing 

<link rel="stylesheet" type="text/css" href="https://skylightanimation.github.io/assets/plugin/font-awesome/4.7.0/css/font-awesome.css">
<link rel="stylesheet" type="text/css" href="https://skylightanimation.github.io/assets/plugin/bootstrap/3.3.7/bootstrap.min.css">
<script type="text/javascript" src="https://skylightanimation.github.io/assets/plugin/jquery/jquery-3.4.1.min.js"></script>
<script type="text/javascript" src="https://skylightanimation.github.io/assets/plugin/bootstrap/3.3.7/bootstrap.min.js"></script>

<div class="container">
	<br>
	<div class="input-group">
		<input type="text" class="form-control" id="text-copy" value="https://LangITTutorial.blogspot.com"> 
		<span class="input-group-btn">
		<button class="btn btn-success copy-btn" type="button">
			<span class="fa fa-copy"></span>
		</button>
		</span>
	</div>
</div>

<script type="text/javascript">
	$(document).ready(function(){
		$('.copy-btn').on("click", function(){
			$("#text-copy").select();
			document.execCommand("copy");
			alert('text copied...');
		})
	})
</script>
