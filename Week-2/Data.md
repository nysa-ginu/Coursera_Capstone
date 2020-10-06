<h2> Data Section for the Car Accident Severity Problem </h2> <hr>
<br>
<p>For the data related to the project, I'll be using the dataset for Car Accident severity in Seattle which was provided in the earlier modules.</p>
<p>We will start off by loadingthe required libraries and the dataset.We will clean the dataset to remove any erroneous or empty values. This will give us a more accurate solution.</p>
<p>This dataset has 37 columns out of which I found only a few to be relevant for my work.</p>
<p>These columns are:</p>
<ul><li>SEVERITYCODE</li>
<li>CCOLLISIONTYPE</li>
<li>WEATHER</li>
<li>ROADCOND</li>
<li>LIGHTCOND</li>
<li>INATTENTIONIND</li>
<li>UNDERINFL</li>
<li>SPEEDING</li>
<li>VEHCOUNT</li>
</ul>
<p>
<ul>
<p>A brief description of what each column represents:</p>
<li><b>SEVERITYCODE</b> is the code given to the collision that corresponds to its severity.</li>
<li><b>WEATHER</b> gives a description of the weather condition during the time of collision.</li>
<li><b>ROADCOND</b> gives the condition of the road during collision.</li>
<li><b>LIGHTCOND</b> gives the light condition during the colllision.</li>
<li><b>INATTENTIONIND</b> tells whether or not the collision was due to inattention.</li>
<li><b>UNDERINFL</b> tells us whether the collision happened because the driver involved was under the influence of drugs or alcohol.</li>
<li><b>SPEEDING</b> tells whether speeding was a factor in the collision or not.</li>
<li><b>VEHCOUNT</b> gives us the number of vehicles involved in the collision. This will help in seeing if it was a multi-car collision or not.</li>
</ul></p>
<p>We will use these information to visualize how these conditions must have played a role in the accident/collision.</p>
