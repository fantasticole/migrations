# Gabs's Project

## Objective

> **Here's what I'm trying to do.**
> I want to add functionality to the onclick for the squares. Right now, the click triggers a tooltip. IN ADDITION, I would like for it to display lines connecting that origin to all of the end circles that apply to it. I hope that makes sense. Basically, trying to trace the migrant journeys from origin to destination, by origin.

> **I think I know how this should be done, in theory.**
> I need to loop through the data array and gather all of the destination (aka end) coordinates by the ORIGIN point, then use that new dataset as the basis for my squares/lines visualization (lines would be made as a MultiLineString object in D3).

> **Here are the main examples I've been studying:**
> https://bl.ocks.org/mbostock/7608400 --> my inspiration; built in D3
> https://stackoverflow.com/questions/39982729/drawing-connecting-lines-great-arcs-on-a-d3-symbol-map/39988387 --> almost exact question I have

> **I'm struggling with how to actually build the loop and execute it. Can you help?**

## Notes
 - I cleaned up the code to better understand what's going on. I didn't really make changes besides making it more readble. Reusable functions are your friend! Let me know if you want to talk more about this :)
 - I also separated the code into multiple files to make it easier to focus on/find the part you're looking for.
 - You want to "display lines connecting that origin to all of the end circles that apply to it." As I understand this
