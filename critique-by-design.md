| [home page](https://cmustudent.github.io/tswd-portfolio-templates/) | [visualizing government debt](visualizing-government-debt) | [final project I](final-project-part-one) | [final project II](final-project-part-two) | [final project III](final-project-part-three) |

# Critique By Design

## Step one: the visualization

This visualization was selected from [MakeoverMonday's](https://makeovermonday.co.uk/) weekly series, which encourages people to hone their data visualization skills through practicing redesign. The example I selected is from National Oceanic and Atmospheric Adminstration (NOAA), regarding abundant levels of Greenhouse Gases in the atmosphere and their relative ability to increase warming. The NOAA webpage seeks to communicate scientific measures of climate change to a more general audience, such as policy makers or educators (NOAA 2024).  This issue is of particular interest to me, as I seek to better understanding the imapcts of climate change on culutral institutions, as a result of increasing levels of Greenhouse Gases. I also am interested in how culutral institutions might interpret this type of information to educating the public. 

Figure 1 shows global average levels of abundance for Carbon Dioxide (CO2), Nitrous Oxide (N2O), Methane (CH4), and other gases. Figure 2 accounts for their relative impact on planetary warming, measured as Radiative Forcing. 

<img src="NOAA-GHG Abundance.png" width="800">

**Figure 1.** 

**Source:** The NOAA Annual Greenhouse Gas Index (AGGI). National Oceanic and Atmospheric Administration. 2024. https://gml.noaa.gov/aggi/aggi.html

<img src="Radiative Forcing.png" width="800">

**Figure 2.**

**Source:** The NOAA Annual Greenhouse Gas Index (AGGI). National Oceanic and Atmospheric Administration. 2024. https://gml.noaa.gov/aggi/aggi.html 


## Step two: the critique
_Note: I conducted my initial critique with a focus on Figure 1.  Using their data set, the chart I ultimatley sketched shared more similar elements with Figure 2 on the NOAA webpage, so I have included both for the purposes of this analysis._ 

**Figure 1** 

While Figure 1 is useful, it tells a fairly limited story - it takes a bit of digging to see exactly what the charts are showing. While you see that it’s relating to a level of these Greenhouses Gases, but the context is not immediately clear. You may easily think it is showing annual emissions for a specific country or region, when it's actually showing global levels of abundant gas in the atmosphere. 

From these charts, it’s easy to see that, in general, Greenhouse Gas levels have increased over time. However, it is very difficult to compare trends between gases, as each has an extremely different scale (parts per million vs. billion vs. trillion). However, by displaying them together in this, this is likely to mislead the viewer to believe that these gases exist at a similar level. And further, they may assume that similar levels of the gas may have similar levels of risk - an assumptions that could prove dangerous in making policy decisions.

In terms of color, there are a number of opportunities to enhance the visualization.  The same color is used across the four charts to represent different gases, which could also lead to confusion in interpreting that chart. Aesthetically, this visualization does not effectively attract or engage more attention. could be improved by reducing alignment points.

**Figure 2**

Figure 2 works to address some of these issues. First, gases are made proportional by multiplying the abundance levels by a warming factor to measure how much it actuall Essentially, this factor representing its warming potential. This makes it much easier to draw comparisons between the gases. However, this visualization also has a number of design considerations that make it challenging to interpret. Using a secondary y-axis, it's very challeneging for the average viewer to interpret what this data means in both planes. Excessive use of color draws eye movement across the graphic, distracting from the key ideas. Additionally, the graphic has an undefined reference line, which inaccurately goes all the way to the x-axis. While this is slightly more truthful in its presentation of information, it has significant opportunities to enhance perceptability, aesthetics, and engagement. 


**Synthesis:**
This material was designed to “enhance the connection between scientists and society by providing a normalized standard that can be easily understood and followed.” While I could see this visualization being effective in communicating within a scientific community, I do not believe it is effective in reaching the general public. With varying scales, jargon, lack of titles, and unclear focus, it would be challenging for an typical individual to understand these visualization without seeking outside information. In my redesign, I want to similify what is presented, showing more persceptible differences in proportion over time. 

## Step three: Sketch a solution

<img src="Sketch 1.png" width="800">

**Visualization by Author.** 

**Data Source:** The NOAA Annual Greenhouse Gas Index (AGGI). National Oceanic and Atmospheric Administration. 2024. https://gml.noaa.gov/aggi/aggi.html 

## Step four: Test the solution

To better understand how this sketch would be interpreted by a more general audience, I tested the proposed sketch with peers. The goal was to see how they interpreted the visualization with limited context and identify opportunities to strengthen the design. Three students from the Heinz College of Information Systems and Public Policy reviewed the sketch and responded to the following prompts: 

- Can you describe what this is telling you?
- Is there anything you find confusing?
- Is there anything you would change or do differently?

**Results:** 

| Question | Interview 1 | Interview 2 | Interview 3 | 
|----------|-------------|-------------|------------|
|Can you describe what this is telling you?  | Greenhouse Gas Emissions | Changes in Emissions Over Time | 
|Is there anything you find confusing?  | Which gas is focus?  | Difficult to see differences in proportion | Meaning of measurements used. 
|Is there anything you would change or do differently?  | Reduce Colors; Use alert color   | Consider bar chart or tree map to show proportions | Enhance title and axis descriptions

**Synthesis:** 

A couple key themes emerged from this feedback - first, that there is opportunity to more clearly articlulate one key story from this visualization. While respondants saw value in this type of chart in showing proportion and changes over time, it was difficult to get a clear understanding differences in proportion, or how they may change over time. This is a known risk of using stacked area graphs, but there are additional design elements that might better. As I move into the final design, I plan to incorporate the following design changes: 

- Focus "story" on Carbon Dioxide (CO2) 
- Use red as an alert color to call attention to Carbon Dioxide on the graph
- Group CFC's and HFC's as "other gases" to reduce number of elements
- Label axes clearly to communicate meaning of measurements
- Use a descriptive title to quickly convey the meaning of the chart

## Step five: build the solution

<img src="Dashboard 1.png" width="800">

**Visualization by Author.** 

**Data Source:** The NOAA Annual Greenhouse Gas Index (AGGI). National Oceanic and Atmospheric Administration. 2024. https://gml.noaa.gov/aggi/aggi.html 


## References
"Improving How We Visualize and Analyze Data." MakeoverMonday. Accessed February 7, 2024. [https://makeovermonday.co.uk/](https://makeovermonday.co.uk/)

"The NOAA Annual Greenhouse Gas Index." Global Monitoring Laboratory, National Oceanic and Atmostpheric Administration. 2024. [https://gml.noaa.gov/aggi/aggi.html](https://gml.noaa.gov/aggi/aggi.html)

