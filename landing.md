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
			<img src="{{ '/assets/images/Average_Max_AQI_per_State.png' | relative_url }}" alt="Description" data-position="center center" />
		</a>
		<div class="content">
			<div class="inner">
				<header class="major">
					<h3>Max_AQI</h3>
				</header>
				<p>We calculate the average maximum AQI per state and visualize it using a bar chart, then we fit the bar chart in our customized AQI secheme with reference to the most commonly used AQI sepcturm. From the chart we can clearly see that Hawaii has the lowest Average AQI, which means it has the greatest air quality overall, and Arkansas has the highest AQI, which means it has the worst air quality overall.</p>
			</div>
		</div>
	</section>
	<section>
		<a href="generic.html" class="image">
			<img src="{{ '/assets/images/Time_Series_of_AQI_Trend.png' | relative_url }}" alt="Description" data-position="top center" />
		</a>
		<div class="content">
			<div class="inner">
				<header class="major">
					<h3>AQI_Time_Trend</h3>
				</header>
				<p>We created a time series analysis with the interactive feature per state to allow specific states to be analyzed to see if AQIs are improving or declining, it helps clean up the data so viewers are able to focus on the regions they are specifically interested in.</p>
			</div>
		</div>
	</section>
	<section>
		<a href="generic.html" class="image">
			<img src="{{ '/assets/images/Heatmap_Average_Max_AQI_per_State.png' | relative_url }}" alt="Description" data-position="25% 25%" />
		</a>
		<div class="content">
			<div class="inner">
				<header class="major">
					<h3>Average_Max_AQI_Heatmap</h3>
				</header>
				<p>We chose to use a heatmap to display the Average Max AQI in a format that allows us to be able to compare states amongst each other. This would be beneficial to recognize which year collectively have worse AQIs but also the regions struggling the most </p>
			</div>
		</div>
	</section>
	<section>
		<a href="generic.html" class="image">
			<img src="{{ '/assets/images/Average_Good_Days_per_State.png' | relative_url }}" alt="Description" data-position="25% 25%" />
		</a>
		<div class="content">
			<div class="inner">
				<header class="major">
					<h3>Average_Good_Days</h3>
				</header>
				<p>We calculated the average number of good air quality days per state with a bar chart. This is also interactive allowing users to choose between the years from 2018 - 2023. We observed that more recent years have seen a decrease in the number of good air quality days. This can be indicative of a worsening air quality condition. </p>
			</div>
		</div>
	</section>
	<section>
		<a href="generic.html" class="image">
			<img src="{{ '/assets/images/Average_Unhealthy_Days_per_State.png' | relative_url }}" alt="Description" data-position="25% 25%" />
		</a>
		<div class="content">
			<div class="inner">
				<header class="major">
					<h3>Average_Unhealthy_Days</h3>
				</header>
				<p>We calculated the average number of unhealthy air quality days per state using a scatterplot. This is also interactive with a dropdown to choose between the years from 2018 - 2023. We noticed that there is an increase in the number of unhealthy days in most states each year; however, the increasing amount is subtle. </p>
			</div>
		</div>
	</section>
	<section>
		<a href="generic.html" class="image">
			<img src="{{ '/assets/images/Air_Quality_Map.png' | relative_url }}" alt="Description" data-position="25% 25%" />
		</a>
		<div class="content">
			<div class="inner">
				<header class="major">
					<h3>Air_Quality_Map</h3>
				</header>
				<p>We created an interactive plot that updates based on the year selected from a dropdown, showing different kinds of AQI rankings and how they compare when looking at a map. This helps us see where AQIs follow a trend based on the region, for examine in the east we can see its considerably and consistency higher than say the midwest.</p>
			</div>
		</div>
	</section>
	
	
</section>

</div>
