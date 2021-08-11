# Homework 4: Design Ethical Visualizations

There are a number of decisions that go into communicating with data and visualizations. The veracity and provenance of data thus becomes increasingly important. In particular, presenting data appropriately becomes an ethics and fairness concern. In this assignment, you will be visualizing a single dataset from two different perspectives: **white hat** and **black hat**.

White hat v. black hat are terms from computer security, where a white hat hacker is someone who uses their skills for good, e.g., finding vulnerabilities in software and systems to help companies and their customers, and a black hat hacker uses them for their own (or their organization's or country's) gain.

A **white hat** visualization is one where:
- The visualizations are clear and easy to interpret for the intended audience (often the general population);
- Any transformations, filtering, and computations done to the data are clearly and transparently communicated; and
- The sources of the data, including potential bias, are communicated.

A **black hat** visualization, on the other hand, exhibits one or several of the following characteristics:
- The visual representation is intentionally inapproporiate, overly complex, and / or too cluttered for the audience;
- Labels, axes, and legends are misleading;
- Titles are skewed to intentionally influence the viewer's perception;
- The data has been transformed, filtered, or processed in an intentionally misleading way; or
- The source and provenance of the data is not clear to the viewer.

## Datasets:
Choose *one* of the following three datasets. Use the same dataset for both visualizations. These datasets are intentionally chosen to cover politically charged topics for the simple reason that these are typically the type of data where ethical visualization is important. Be warned that some of these topics can be disturbing; avoid datasets that are difficult for you personally. *Note: You do not have to visualization the entire dataset! You may choose a subset of the data to visualize. This is useful because some of the datasets below are larger than others.*
- **U.S. Mass Shootings 1982-2019**: a spreadsheet of mass shootings in the United States 
- **OECD Greenhouse Gas Emissions 1990-2017**: emissions from different counties over the years
- **New York City Police Complaints**: complaints filed against the NYPD 

## Submission:
You will generate *two* visualizations in total (one white hat, one black hat). You are free to use any visualization technique and any visualization tool (or even draw by hand) to generate each submission. The white and black hat visualizations do not have to use the same tool or technique. For each visualization, include the following: 
1. title (short sentence) describing the visualization,
2. legend (if necessary),
3. one-paragraph description of what the visualization shows (i.e., what dataset, attributes, trend, etc. is being depicted),
4. clear annotation about which visualization is "white hat" and which is "black hat",
5. one-paragraph description of design motivation, indicating the choice of visual encodings used and how it supports the goal of "white hat" or "black hat" presentation of data, and
6. the following disclaimer: 
> *DISCLAIMER: This visualization was created as part of a visualization ethics assignment. Please use the information presented here with caution, as it may have been intentionally designed to be misleading.*

## Tips:
- There are limits to what you can do for the black hat visualization; for example, it doesn’t make sense to make up data entirely (but you may be forgiven for filtering inconvenient outliers).
- Similarly, it is interesting to consider that the notion of “black” vs “white” could depend on your political affiliation, personality, and background. However, you should strive to avoid this becoming an exercise in partisanship, but rather view black hat as being about obfuscation and white hat being about transparency.
- For the white hat visualization, it is not sufficient to just create a standard visualization and be done with it; you need to actively work to make your visualization as clear and transparent as possible!

### Acknowledgments: 
This assignment was adapted from a [blog post by Niklas Elmqvist](https://niklaselmqvist.medium.com/teaching-ethics-for-visualization-b48e3ced84df).

Data was obtained from the following sources:
- U.S. Mass Shootings 1982-2019: [Mother Jones](https://www.motherjones.com/politics/2012/12/mass-shootings-mother-jones-full-data/)
- OECD Greenhouse Gas Emissions 1990-2017: [OECD Statistics](https://stats.oecd.org/Index.aspx?DataSetCode=AIR_GHG)
- New York City Police Complaints: [ProPublica](https://www.propublica.org/datastore/dataset/civilian-complaints-against-new-york-city-police-officers)
