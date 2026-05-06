# NBA Scoring Versatility and Playoff Performance Analysis

This project analyzes how NBA scoring versatility relates to playoff efficiency decline using Python, Pandas, Matplotlib, and NBA API shot-location data.

## Project Objective

The original hypothesis was that 3-level scorers would experience the smallest playoff efficiency decline because of their ability to score from the interior, midrange, and three-point range.

After expanding the analysis across multiple NBA seasons, the results revealed a more nuanced pattern.

## Key Findings

- 1-level scorers experienced the smallest average playoff TS% decline.
- 2-level scorers experienced the largest average decline.
- 3-level scorers remained relatively stable and consistently performed better than 2-level scorers.
- Midrange FG% was the most stable shot zone across the playoff sample.
- Interior scoring declined the most, likely due to increased rim protection and physicality.

## Tools Used

- Python
- Pandas
- NumPy
- Matplotlib
- NBA API
- Google Colab
- GitHub

## Methods

- Pulled NBA regular season and playoff data using the NBA API.
- Classified players into 1-level, 2-level, and 3-level scoring archetypes based on shot-location distribution.
- Compared regular season vs playoff True Shooting Percentage changes.
- Validated findings across multiple NBA seasons.
- Built custom visualizations, including bar charts, line charts, box plots, scatter plots, and court-style shot zone maps.

## Main Takeaway

Playoff basketball does not simply reward the most efficient regular-season shots. It rewards the scoring options defenses cannot fully take away.

In this analysis, the midrange emerged as the most stable scoring zone under playoff pressure.
