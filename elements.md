---
layout: page
title: Outline
image: assets/images/pic01.jpg
nav-menu: true
---

<!-- Main -->
<div id="main" class="alt">

<!-- One -->
<section id="one">
	<div class="inner">
		<header class="major">
			<h1>Elements</h1>
		</header>

<!-- Content -->
<h2 id="content">Purpose and Outline</h2>
<p>The purpose of this assignment is to create a 'Viz for Experts' with an interactive dashboard interface for exploring your data.</p>

<p>For this submission option, you will submit your work through this Workspace.</p>

<p><strong>Please see Homework Prompt in PrairieLearn interface for more details on the requirements for this assignment.</strong></p>

<p>A rough outline of elements of code and write-up is shown below:</p>
<div class="row">
	<div class="6u 12u$(small)">
		<h3><strong>1. Data Preparation</strong></h3>
		<p>1.1. Import necessary libraries.</p>
		<p>1.2. Read the dataset and perform any initial data filtering or cleaning.</p>
	</div>
	<div class="6u$ 12u$(small)">
		<h3><strong>2. Data Visualization</strong></h3>
		<p>Six visualizations were built.</p>
		<p>2.1. max_aqi (2): Calculate the average maximum AQI per state and visualize it using a bar chart and a heatmap.</p>
  		<p>2.2. good_days (1): Calculate and visualize the average number of good air quality days per state with a bar chart.</p>
    		<p>2.3. unhealthy_days (1): Calculate and visualize the average number of bad air quality days per state with a bar chart and a year selector.</p>
      		<p>2.4. air_quality_map (1): Create an interactive plot that updates based on the year selected from a dropdown, showing different kinds of day counts.</p>
		<p>2.5. aqi_trend (1): Plot the trend of AQI over the years for a selected state using a line plot with a trend line.</p>
	</div>
	<!-- Break -->
	<div class="4u 12u$(medium)">
		<h3><strong>3. Building Dashboard and refresh button</strong></h3>
		<p>3.1. Organize the individual visualizations into a tabbed layout using ipywidgets.tab, with each tab corresponding to a different visualization of the air quality data as shown above.</p>
		<p>3.2. Build a refresh button to update all visualizations with new data if needed.</p>
	</div>
</div>

<hr class="major" />

<!-- Elements -->
<h2 id="elements">Elements</h2>
<div class="row 200%">
	<div class="6u 12u$(medium)">

<!-- Text stuff -->
<h3>Text</h3>
<p>This is <b>bold</b> and this is <strong>strong</strong>. This is <i>italic</i> and this is <em>emphasized</em>.
This is <sup>superscript</sup> text and this is <sub>subscript</sub> text.
This is <u>underlined</u> and this is code: <code>for (;;) { ... }</code>.
Finally, this is a <a href="#">link</a>.</p>
<hr />
<h2>Heading Level 2</h2>
<h3>Heading Level 3</h3>
<h4>Heading Level 4</h4>
<hr />
<p>Nunc lacinia ante nunc ac lobortis. Interdum adipiscing gravida odio porttitor sem non mi integer non faucibus ornare mi ut ante amet placerat aliquet. Volutpat eu sed ante lacinia sapien lorem accumsan varius montes viverra nibh in adipiscing blandit tempus accumsan.</p>

<!-- Lists -->
<h3>Lists</h3>
<div class="row">
	<div class="6u 12u$(small)">

		<h4>Unordered</h4>
		<ul>
			<li>Dolor etiam magna etiam.</li>
			<li>Sagittis lorem eleifend.</li>
			<li>Felis dolore viverra.</li>
		</ul>

		<h4>Alternate</h4>
		<ul class="alt">
			<li>Dolor etiam magna etiam.</li>
			<li>Sagittis lorem eleifend.</li>
			<li>Felis feugiat viverra.</li>
		</ul>

	</div>
	<div class="6u$ 12u$(small)">

		<h4>Ordered</h4>
		<ol>
			<li>Dolor etiam magna etiam.</li>
			<li>Etiam vel lorem sed viverra.</li>
			<li>Felis dolore viverra.</li>
			<li>Dolor etiam magna etiam.</li>
			<li>Etiam vel lorem sed viverra.</li>
			<li>Felis dolore viverra.</li>
		</ol>

		<h4>Icons</h4>
		<ul class="icons">
			<li><a href="#" class="icon fa-twitter"><span class="label">Twitter</span></a></li>
			<li><a href="#" class="icon fa-facebook"><span class="label">Facebook</span></a></li>
			<li><a href="#" class="icon fa-instagram"><span class="label">Instagram</span></a></li>
			<li><a href="#" class="icon fa-github"><span class="label">Github</span></a></li>
			<li><a href="#" class="icon fa-dribbble"><span class="label">Dribbble</span></a></li>
			<li><a href="#" class="icon fa-tumblr"><span class="label">Tumblr</span></a></li>
		</ul>
		<ul class="icons">
			<li><a href="#" class="icon alt fa-twitter"><span class="label">Twitter</span></a></li>
			<li><a href="#" class="icon alt fa-facebook"><span class="label">Facebook</span></a></li>
			<li><a href="#" class="icon alt fa-instagram"><span class="label">Instagram</span></a></li>
		</ul>

	</div>
</div>

<h4>Definition</h4>
<dl>
	<dt>Item1</dt>
	<dd>
		<p>Lorem ipsum dolor vestibulum ante ipsum primis in faucibus vestibulum. Blandit adipiscing eu felis iaculis volutpat ac adipiscing accumsan eu faucibus. Integer ac pellentesque praesent. Lorem ipsum dolor.</p>
	</dd>
	<dt>Item2</dt>
	<dd>
		<p>Lorem ipsum dolor vestibulum ante ipsum primis in faucibus vestibulum. Blandit adipiscing eu felis iaculis volutpat ac adipiscing accumsan eu faucibus. Integer ac pellentesque praesent. Lorem ipsum dolor.</p>
	</dd>
	<dt>Item3</dt>
	<dd>
		<p>Lorem ipsum dolor vestibulum ante ipsum primis in faucibus vestibulum. Blandit adipiscing eu felis iaculis volutpat ac adipiscing accumsan eu faucibus. Integer ac pellentesque praesent. Lorem ipsum dolor.</p>
	</dd>
</dl>

<h4>Actions</h4>
<ul class="actions">
	<li><a href="#" class="button special">Default</a></li>
	<li><a href="#" class="button">Default</a></li>
</ul>
<ul class="actions small">
	<li><a href="#" class="button special small">Small</a></li>
	<li><a href="#" class="button small">Small</a></li>
</ul>
<div class="row">
	<div class="6u 12u$(small)">
		<ul class="actions vertical">
			<li><a href="#" class="button special">Default</a></li>
			<li><a href="#" class="button">Default</a></li>
		</ul>
	</div>
	<div class="6u$ 12u$(small)">
		<ul class="actions vertical small">
			<li><a href="#" class="button special small">Small</a></li>
			<li><a href="#" class="button small">Small</a></li>
		</ul>
	</div>
	<div class="6u 12u$(small)">
		<ul class="actions vertical">
			<li><a href="#" class="button special fit">Default</a></li>
			<li><a href="#" class="button fit">Default</a></li>
		</ul>
	</div>
	<div class="6u$ 12u$(small)">
		<ul class="actions vertical small">
			<li><a href="#" class="button special small fit">Small</a></li>
			<li><a href="#" class="button small fit">Small</a></li>
		</ul>
	</div>
</div>

<!-- Blockquote -->
<h3>Blockquote</h3>
<blockquote>Fringilla nisl. Donec accumsan interdum nisi, quis tincidunt felis sagittis eget tempus euismod. Vestibulum ante ipsum primis in faucibus vestibulum. Blandit adipiscing eu felis iaculis volutpat ac adipiscing accumsan faucibus. Vestibulum ante ipsum primis in faucibus vestibulum. Blandit adipiscing eu felis.</blockquote>

<!-- Table -->
<h3>Table</h3>

<h4>Default</h4>
<div class="table-wrapper">
	<table>
		<thead>
			<tr>
				<th>Name</th>
				<th>Description</th>
				<th>Price</th>
			</tr>
		</thead>
		<tbody>
			<tr>
				<td>Item1</td>
				<td>Ante turpis integer aliquet porttitor.</td>
				<td>29.99</td>
			</tr>
			<tr>
				<td>Item2</td>
				<td>Vis ac commodo adipiscing arcu aliquet.</td>
				<td>19.99</td>
			</tr>
			<tr>
				<td>Item3</td>
				<td> Morbi faucibus arcu accumsan lorem.</td>
				<td>29.99</td>
			</tr>
			<tr>
				<td>Item4</td>
				<td>Vitae integer tempus condimentum.</td>
				<td>19.99</td>
			</tr>
			<tr>
				<td>Item5</td>
				<td>Ante turpis integer aliquet porttitor.</td>
				<td>29.99</td>
			</tr>
		</tbody>
		<tfoot>
			<tr>
				<td colspan="2"></td>
				<td>100.00</td>
			</tr>
		</tfoot>
	</table>
</div>

<h4>Alternate</h4>
<div class="table-wrapper">
	<table class="alt">
		<thead>
			<tr>
				<th>Name</th>
				<th>Description</th>
				<th>Price</th>
			</tr>
		</thead>
		<tbody>
			<tr>
				<td>Item1</td>
				<td>Ante turpis integer aliquet porttitor.</td>
				<td>29.99</td>
			</tr>
			<tr>
				<td>Item2</td>
				<td>Vis ac commodo adipiscing arcu aliquet.</td>
				<td>19.99</td>
			</tr>
			<tr>
				<td>Item3</td>
				<td> Morbi faucibus arcu accumsan lorem.</td>
				<td>29.99</td>
			</tr>
			<tr>
				<td>Item4</td>
				<td>Vitae integer tempus condimentum.</td>
				<td>19.99</td>
			</tr>
			<tr>
				<td>Item5</td>
				<td>Ante turpis integer aliquet porttitor.</td>
				<td>29.99</td>
			</tr>
		</tbody>
		<tfoot>
			<tr>
				<td colspan="2"></td>
				<td>100.00</td>
			</tr>
		</tfoot>
	</table>
</div>

</div>
<div class="6u$ 12u$(medium)">

<!-- Buttons -->
<h3>Buttons</h3>
<ul class="actions">
	<li><a href="#" class="button special">Special</a></li>
	<li><a href="#" class="button">Default</a></li>
</ul>
<ul class="actions">
	<li><a href="#" class="button big">Big</a></li>
	<li><a href="#" class="button">Default</a></li>
	<li><a href="#" class="button small">Small</a></li>
</ul>
<ul class="actions">
	<li><a href="#" class="button special big">Big</a></li>
	<li><a href="#" class="button special">Default</a></li>
	<li><a href="#" class="button special small">Small</a></li>
</ul>
<ul class="actions fit">
	<li><a href="#" class="button special fit">Fit</a></li>
	<li><a href="#" class="button fit">Fit</a></li>
</ul>
<ul class="actions fit small">
	<li><a href="#" class="button special fit small">Fit + Small</a></li>
	<li><a href="#" class="button fit small">Fit + Small</a></li>
</ul>
<ul class="actions">
	<li><a href="#" class="button special icon fa-search">Icon</a></li>
	<li><a href="#" class="button icon fa-download">Icon</a></li>
</ul>
<ul class="actions">
	<li><span class="button special disabled">Special</span></li>
	<li><span class="button disabled">Default</span></li>
</ul>

<!-- Form -->
<h3>Form</h3>

<form method="post" action="#">
	<div class="row uniform">
		<div class="6u 12u$(xsmall)">
			<input type="text" name="demo-name" id="demo-name" value="" placeholder="Name" />
		</div>
		<div class="6u$ 12u$(xsmall)">
			<input type="email" name="demo-email" id="demo-email" value="" placeholder="Email" />
		</div>
		<!-- Break -->
		<div class="12u$">
			<div class="select-wrapper">
				<select name="demo-category" id="demo-category">
					<option value="">- Category -</option>
					<option value="1">Manufacturing</option>
					<option value="1">Shipping</option>
					<option value="1">Administration</option>
					<option value="1">Human Resources</option>
				</select>
			</div>
		</div>
		<!-- Break -->
		<div class="4u 12u$(small)">
			<input type="radio" id="demo-priority-low" name="demo-priority" checked>
			<label for="demo-priority-low">Low</label>
		</div>
		<div class="4u 12u$(small)">
			<input type="radio" id="demo-priority-normal" name="demo-priority">
			<label for="demo-priority-normal">Normal</label>
		</div>
		<div class="4u$ 12u$(small)">
			<input type="radio" id="demo-priority-high" name="demo-priority">
			<label for="demo-priority-high">High</label>
		</div>
		<!-- Break -->
		<div class="6u 12u$(small)">
			<input type="checkbox" id="demo-copy" name="demo-copy">
			<label for="demo-copy">Email me a copy</label>
		</div>
		<div class="6u$ 12u$(small)">
			<input type="checkbox" id="demo-human" name="demo-human" checked>
			<label for="demo-human">I am a human</label>
		</div>
		<!-- Break -->
		<div class="12u$">
			<textarea name="demo-message" id="demo-message" placeholder="Enter your message" rows="6"></textarea>
		</div>
		<!-- Break -->
		<div class="12u$">
			<ul class="actions">
				<li><input type="submit" value="Send Message" class="special" /></li>
				<li><input type="reset" value="Reset" /></li>
			</ul>
		</div>
	</div>
</form>

<!-- Image -->
<h3>Image</h3>

<h4>Fit</h4>
<span class="image fit"><img src="{% link assets/images/pic03.jpg %}" alt="" /></span>
<div class="box alt">
	<div class="row 50% uniform">
		<div class="4u"><span class="image fit"><img src="{% link assets/images/pic08.jpg %}" alt="" /></span></div>
		<div class="4u"><span class="image fit"><img src="{% link assets/images/pic09.jpg %}" alt="" /></span></div>
		<div class="4u$"><span class="image fit"><img src="{% link assets/images/pic10.jpg %}" alt="" /></span></div>
		<!-- Break -->
		<div class="4u"><span class="image fit"><img src="{% link assets/images/pic10.jpg %}" alt="" /></span></div>
		<div class="4u"><span class="image fit"><img src="{% link assets/images/pic08.jpg %}" alt="" /></span></div>
		<div class="4u$"><span class="image fit"><img src="{% link assets/images/pic09.jpg %}" alt="" /></span></div>
		<!-- Break -->
		<div class="4u"><span class="image fit"><img src="{% link assets/images/pic09.jpg %}" alt="" /></span></div>
		<div class="4u"><span class="image fit"><img src="{% link assets/images/pic10.jpg %}" alt="" /></span></div>
		<div class="4u$"><span class="image fit"><img src="{% link assets/images/pic08.jpg %}" alt="" /></span></div>
	</div>
</div>

<h4>Left &amp; Right</h4>
<p><span class="image left"><img src="{% link assets/images/pic09.jpg %}" alt="" /></span>Lorem ipsum dolor sit accumsan interdum nisi, quis tincidunt felis sagittis eget. tempus euismod. Vestibulum ante ipsum primis in faucibus vestibulum. Blandit adipiscing eu felis iaculis volutpat ac adipiscing accumsan eu faucibus. Integer ac pellentesque praesent tincidunt felis sagittis eget. tempus euismod. Vestibulum ante ipsum primis sagittis eget. tempus euismod. Vestibulum ante ipsum primis in faucibus vestibulum. Blandit adipiscing eu felis iaculis volutpat ac adipiscing accumsan eu faucibus. Integer ac pellentesque praesent tincidunt felis sagittis eget tempus vestibulum ante ipsum primis in faucibus magna blandit adipiscing eu felis iaculis.</p>
<p><span class="image right"><img src="{% link assets/images/pic10.jpg %}" alt="" /></span>Lorem ipsum dolor sit accumsan interdum nisi, quis tincidunt felis sagittis eget. tempus euismod. Vestibulum ante ipsum primis in faucibus vestibulum. Blandit adipiscing eu felis iaculis volutpat ac adipiscing accumsan eu faucibus. Integer ac pellentesque praesent tincidunt felis sagittis eget. tempus euismod. Vestibulum ante ipsum primis sagittis eget. tempus euismod. Vestibulum ante ipsum primis in faucibus vestibulum. Blandit adipiscing eu felis iaculis volutpat ac adipiscing accumsan eu faucibus. Integer ac pellentesque praesent tincidunt felis sagittis eget tempus vestibulum ante ipsum primis in faucibus magna blandit adipiscing eu felis iaculis.</p>

<!-- Box -->
<h3>Box</h3>
<div class="box">
	<p>Felis sagittis eget tempus primis in faucibus vestibulum. Blandit adipiscing eu felis iaculis volutpat ac adipiscing accumsan eu faucibus. Integer ac pellentesque praesent tincidunt felis sagittis eget. tempus euismod. Magna sed etiam ante ipsum primis in faucibus vestibulum. Blandit adipiscing eu ipsum primis in faucibus vestibulum. Blandit adipiscing eu felis iaculis volutpat ac adipiscing accumsan eu faucibus lorem ipsum.</p>
</div>

<!-- Preformatted Code -->
<h3>Preformatted</h3>
<pre><code>i = 0;

while (!deck.isInOrder()) {
    print 'Iteration ' + i;
    deck.shuffle();
    i++;
}

print 'It took ' + i + ' iterations to sort the deck.';
</code></pre>

</div>
</div>

</div>
</section>

</div>