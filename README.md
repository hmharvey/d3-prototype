# d3.js: prototypes and working charts for Clarity

__What is Clarity?__

Clarity is a personal information management tool that uses interactive data visualizations to help individuals track important information. With this tool, users can upload and organize overarching topics with specific personal perspectives. Users can also add sources to back up their perspectives, and filter sources based on different information. I've worked on this project since June 2017.

__My contributions__

I built a series of interactive charts using [d3.js](https://d3js.org/), utilizing the control of forces to pull the graph along the x and y axes and create links between each node. After building out these prototypes, I integrated the charts into a working Ember app, using SCSS and hooking them up to APIs. 

__Tech stack__

d3.js, Ember

__Status__

Clarity is currently in private alpha. More information can be found in [this case study](https://www.michelle.codes/work/clarity/).

## Philosophies Graph
This graph shows the overarching topics (green) and specific ideas (blue) within each topic through a visual graph to clearly show the links and categorize the information.
![worldview-index](Prototype-Gifs/Index.gif)

## Sources Graph
This graph shows all of the sources used within your tool. The key isn't shown, but each color correlates to a type of source, such as book, talk, podcast, etc. This utility of this graph allows for the beginning of analysis of your sources, separating by type (the process which will also be used to separate sources based on author gender and/or ethnicity) as well as allowing the influence of each source be toggled. In the initial layout, the circles are different sizes based on how many perspectives the source supports. However, you can also change all the sizes to be the same static size which allows for a slightly different set of analysis.
![sources-index](Prototype-Gifs/Sources-Index.gif)

## Dot Plot Graph
This graph will be used, without the axes, to show combinations of filters that can't be accomplished with the above Sources Graph. For example, the sources could be lined up to show both gender and ethnicity
![dot-plot-index](Prototype-Gifs/Dot-Plot-Index.gif)
