# flyout-boxes

## Tutorial		  
For detailed instruction's, view Solodev's [How to Make Animated Toolbox Flyouts](https://www.solodev.com/blog/how-to-make-animated-toolbox-flyouts.stml) article.
 
## Demo
  		  
Try out a working example on [JSFiddle](https://jsfiddle.net/solodev/ox7vu4hp/82/).

## HTML

The tutorial contains the following basic HTML markup.

```
<section>
    <img alt="Powering web experiences across the planet" class="img-fluid d-block mx-auto" src="https://www.solodev.com/_/images/powering-the-planet.png">
</section>
<div class="container">
	<div class="row">
		<div class="col-sm-12">
			<h1 class="text-center display-3 my-5">Solodev integrates with most favorite platform</h1>
		</div>
	</div>
	<div class="row">
		<div class="col-sm-12 toolbox">
			<div class="toolbox-item" onclick="location.href='#'">
				<a href="#">
					<div class="row">
						<div class="col-xs-12">
						    <img src="https://raw.githubusercontent.com/solodev/flyout-boxes/master/salesforce-icon.png" alt="salesforce icon" class="img-fluid"/> <span>SalesForce</span>
						</div>
					</div>
				</a>
				<div class="more">
					<p>Integrate with SalesForce - the most popular CRM system on the planet.</p>
				</div>
			</div><!-- item-->
			<div class="toolbox-item" onclick="location.href='#'">
				<a href="#">
					<div class="row">
						<div class="col-xs-12">
						     <img src="https://raw.githubusercontent.com/solodev/flyout-boxes/master/integration-solodev-mailchimp-icon.png" alt="mailchimp icon" class="img-fluid"/><span>MailChimp</span>
						</div>
					</div>
				</a>
				<div class="more">
					<p>Integrate with MailChimp and create web hooks to collect data in real time.</p>
				</div>
			</div><!-- item-->
		</div>
	</div>
</div>

```

## CSS

All required CSS is contained with style.css


## External Resources

This tutorial includes the following third party resources.

```
<link href="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0-alpha.6/css/bootstrap.min.css" rel="stylesheet">
<script src="https://code.jquery.com/jquery-3.2.1.slim.min.js"></script>
<script src="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0-alpha.6/js/bootstrap.min.js"></script>
```

