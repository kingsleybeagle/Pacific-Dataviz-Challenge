# Pacific Dataviz Challenge
My entry for the 2026 Pacific Dataviz Challenge.

# Climate Change: The Pacific Catch-22

## Project Summary
This project analyses the dynamics between tourism reliance, renewable energy share, and decarbonisation opportunities across select Pacific Island locations. Using K-Means clustering and dynamic revenue modelling, it proposes a Shared Pacific Resilience Fund driven by a modest visitor levy ($1–$20/visitor) to fund localised grid decarbonisation.

This submission is entered into the interactive category. As the Power BI report has not been published to a public workspace, the file has been uploaded into this repository, and a static export of the file has been included to enable users to view the content. Additionally, GIFs showcasing some interactive aspects of the report are embedded below. For the best experience, I recommend downloading the pbix file and exploring the report within Power BI desktop.

Within notebooks and processed data, I have retained commentary and engineered features pertaining to project outcomes which were not implemented. These have been retained to transparently demonstrate the design and development process. 

As required by the Pacific Dataviz Challenge, this project uses datasets from the Pacific Data Hub.

### Full Report (static)
![Pacific Dataviz Challenge 2026](<Pacific Dataviz Challenge 2026/submission/Pacific Dataviz Challenge Screenshot.png>)
_Figure 1: Full report overview_
<br><br>

### Animations Demonstratiting Interactive Elements
![Pacific Dataviz Challenge 2026](<Pacific Dataviz Challenge 2026/gifs/scatter.gif>)
_Figure 2: Demonstration of scatter chart changes for individual locations (between 2000-2019)_
<br><br>
<br><br>

![Pacific Dataviz Challenge 2026](<Pacific Dataviz Challenge 2026/gifs/cook_islands.gif>)
_Figure 3: Demonstration of selecting a single cluster (right hand side) and single location (trailing line for Cook Islands)_<br>
_Note: Selection of this cluster shows how Niue and Palau transition into the cluster_
<br><br>
<br><br>

![Pacific Dataviz Challenge 2026](<Pacific Dataviz Challenge 2026/gifs/line_charts.gif>)
_Figure 4: Demonstration of the different features (y axis)_
<br><br>
<br><br>

![Pacific Dataviz Challenge 2026](<Pacific Dataviz Challenge 2026/gifs/levy.gif>)
_Figure 5: Demonstration of how proposed levy value changes the total projection over a 10 year period_
<br><br>

## Use of AI
I used Google Gemini to assist in the development of this project. Although useful as a sounding board, the unlimited directions that Gemini offered regarding where my project could go (and the relentless optimism that Gemini approached each one with) meant that it was very easy to follow lines of enquiry that were problematic because they did one of the following:
* Deviated from the project brief
* Suggested approaches that I was not familiar with (which isn't necessarily a bad thing, but I was time bound)
* Didn't account for real world nuance and necessary trade-offs

As such, early iterations of this project included Streamlit apps, Piecewise Linear Regression, and comparisons of Pacific Island tourist initiatives against those from the Galapagos Islands. 

The more I engaged with Gemini, the more questions I had, and the more doubts I had. This resulted in too many hours of prompting and noting down ideas, and too little actual output (I spent more time optimising prompts, rather than actually producing dataviz). I therefore went back to basics and used pen and paper to sketch out the below (human generated) foundations from which the rest of my work was built.

<br><br>
<p align="center">
  <img src="Pacific Dataviz Challenge 2026/design ideas/initial_sketch-1.png" alt="sketch 1" width="600" style="margin-bottom: 24px;">
</p>
_Figure 6: Sketch Page 1_
<br><br>
<br><br>
<p align="center">
  <img src="Pacific Dataviz Challenge 2026/design ideas/initial_sketch-2.png" alt="sketch 2" width="600" style="margin-bottom: 24px;">
</p>
_Figure 7: Sketch Page 2_
<br><br>
<br><br>
<p align="center">
  <img src="Pacific Dataviz Challenge 2026/design ideas/initial_sketch-3.png" alt="sketch 3" width="600" style="margin-bottom: 24px;">
</p>
_Figure 8: Sketch Page 3_
<br><br>
<br><br>

After completing this process everything from then on out felt productive and aligned to the project requirements, I spent the next week or two iterating on my submission.

A pivotal moment in the project came when I decided to switch from the my sketched design format (three page dashboard) to a long form style report. This achieved a final output that was less complex than I originally planned, while delivering a flow felt that felt more appropriate to the project context. The end result was a bespoke single page report designed for exploration which interactively took the user on a journey from observation to context to suggestions.  

I was very happy with how my report turned out, and I found that AI was most productive as a design aid when used to explore aesthetic changes.