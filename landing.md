---
title: Visualizations & Explanations
layout: landing
description: 'In this part, we will display our visualizations in detail.'
image: assets/images/Time_Series_of_AQI_Trend.png
nav-menu: true
---

<!-- Main -->
<div id="main">

<!-- One -->
<section id="one">
	<div class="inner">
		<p>There are 6 visualizations we built.</p>
	</div>
</section>

<!-- Two -->
<section id="two" class="spotlights">
	<section>
		<a href="generic.html" class="image">
			<img src="{% link /Final_Group_Project/assets/images/Average_Max_AQI_per_State.png %}" alt="" data-position="center center" />
		</a>
		<div class="content">
			<div class="inner">
				<header class="major">
					<h3>Max_AQI</h3>
				</header>
				<p>We calculate the average maximum AQI per state and visualize it using a bar chart, then we fit the bar chart in our customized AQI sepcturm with reference to the most commonly used AQI sepcturm.</p>
			</div>
		</div>
	</section>
	<section>
		<a href="generic.html" class="image">
			<img src="{% link /Final_Group_Project/assets/images/Time_Series_of_AQI_Trend.png %}" alt="" data-position="top center" />
		</a>
		<div class="content">
			<div class="inner">
				<header class="major">
					<h3>AQI_Time_Trend</h3>
				</header>
				<p>We plot the trend of AQI over the years for a selected state using a line plot with a trend line.</p>
			</div>
		</div>
	</section>
	<section>
		<a href="generic.html" class="image">
			<img src="{% link /Final_Group_Project/assets/images/Heatmap_Average_Max_AQI_per_State.png %}" alt="" data-position="25% 25%" />
		</a>
		<div class="content">
			<div class="inner">
				<header class="major">
					<h3>Average_Max_AQI_Heatmap</h3>
				</header>
				<p>We then using a heatmap to illustrate the Average Max AQI among States.</p>
			</div>
		</div>
	</section>
	<section>
		<a href="generic.html" class="image">
			<img src="{% link /Final_Group_Project/assets/images/Average_Good_Days_per_State.png %}" alt="" data-position="25% 25%" />
		</a>
		<div class="content">
			<div class="inner">
				<header class="major">
					<h3>Average_Good_Days</h3>
				</header>
				<p>We also calculate and visualize the average number of good air quality days per state with a bar chart, which is also interactive and allows users to change the year from the dropdown.</p>
			</div>
		</div>
	</section>
	<section>
		<a href="generic.html" class="image">
			<img src="{% link /Final_Group_Project/assets/images/Average_Unhealthy_Days_per_State.png %}" alt="" data-position="25% 25%" />
		</a>
		<div class="content">
			<div class="inner">
				<header class="major">
					<h3>Average_Unhealthy_Days</h3>
				</header>
				<p>We calculate and visualize the average number of bad air quality days per state with a bar chart and a year selector.</p>
			</div>
		</div>
	</section>
	<section>
		<a href="generic.html" class="image">
			<img src="{% link /Final_Group_Project/assets/images/Air_Quality_Map.png %}" alt="" data-position="25% 25%" />
		</a>
		<div class="content">
			<div class="inner">
				<header class="major">
					<h3>Air_Quality_Map</h3>
				</header>
				<p>We created an interactive plot that updates based on the year selected from a dropdown, showing different kinds of day counts.</p>
			</div>
		</div>
	</section>
	
	
</section>

</div>
