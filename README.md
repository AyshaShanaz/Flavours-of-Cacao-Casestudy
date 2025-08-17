# Flavours-of-Cacao-Casestudy

Overview

Examines global chocolate bar ratings to understand relationships between cocoa percentage, origin, bean variety, and expert reviews. Helps consumers and producers explore characteristics linked to higher ratings.

Objectives

Distribution of ratings by maker and origin.
Relationship between cocoa percentage and rating.
Comparisons by bean varieties and processing styles.
Top producers and regions by average rating.

Data Sources

Flavors of Cacao dataset: maker, origin, cocoa percent, bean type, rating.
Supplemental country/region mapping for maps.

Methodology

Clean cocoa percentage to numeric (e.g., 70% to 70).
Handle missing bean types/origins; group rare categories.
Aggregate by maker and origin; compute average/median ratings.
Visualize relationships (scatter), distributions (histogram), and geography (choropleth).

Key Views and Interactions

Scatter: cocoa percentage vs. rating with trend line.
Ranked bars: top makers and origins by average rating.
Filters: bean type, maker, region, year (if available).
Map: origins shaded by average rating or count.

Findings and Insights

Higher ratings often cluster around 65–75% cocoa; diminishing returns at very high percentages.
Some origins consistently outperform, suggesting terroir and supply chain quality effects.
Maker consistency matters; regular producers outperform sporadic entrants.

Limitations

Expert ratings may not generalize to all consumers.
Uneven dataset coverage by year/region.
Cocoa percentage is an imperfect proxy for flavor complexity.

How to View
Open: flavours_of_cacao.html

