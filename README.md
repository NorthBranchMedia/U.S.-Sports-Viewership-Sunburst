# U.S. Sports Viewership Sunburst

## Preview

![Sunburst](sunburst.png)

--

## Overview

Sunburst chart displaying U.S. sports viewership accross the 52 weeks of the year. Each segment covers one week of sports with each arc segment representing the average U.S. English-language linear television broadcast viewers of the most watched event for that particular league (Spanish-language broadcasts are included for some international soccer events as noted).

For leagues not in season at the time of publishing, the most recent full season is diplayed. For leagues currently in season (or leagues/events that do not operate on a season model), the most recent 12 months of competition is displayed. Streaming views are excluded for the majority of segments with the notable exception of the 2024 Paris Olympics, which in addition to NBC viewers inculdes views on Peacock.

This visualization covers most sporting events viewed in the U.S, with the most notable exclusion being the Jake Paul vs. Mike Tyson boxing match on November 14th, 2024. The fight was aired on Netflix and garnered 60M views globally. I chose not to include it as it was not sanctioned by the WBA, WBC, IBF or WBO. Additional exclusions include the WNBA, LIV Golf and NCAA Men's Wrestling.

--

## Data
Dataset (`US_Sports_Viewership_2024-2025_Combined_09.28.2025`) consolidates televised sports events into a single baseline covering weekly viewership numbers.  
- Columns: `league,	viz_week_index, week_start_date_utc,	week_end_date_utc	game,	network,	avg_viewers_millions,	source_url`
- Values are in millions of viewers 

--

## Visualization
The visualization is housed in [Observable](https://observablehq.com/d/160e3f09561cd8b2) using **D3.js**.  

--

## License
MIT License — free to reuse with attribution.  

--

## Credits
- Visualization built with **D3.js** in Observable
- Special thanks to Jon Lewis for curating such comprehensive data on the subject on [Sports Media Watch](https://www.sportsmediawatch.com/)
