# Sports Roster Data Project

This organization maintains scrapers, datasets, and cleaning scripts for NCAA college sports rosters. It is a project of the [Philip Merrill College of Journalism](https://merrill.umd.edu/) at the University of Maryland, developed through coursework and ongoing research and led by Derek Willis, a lecturer in data and computational journalism.

The goal is straightforward: make roster data easier to work with. NCAA team websites are inconsistent, and player information — positions, hometowns, heights, previous schools — is often formatted differently from one program to the next. The repositories here collect that data, standardize it where possible, and make it available in CSV and JSON formats.

## Repositories

| Repository | Description |
|---|---|
| [womens-college-basketball](https://github.com/Sports-Roster-Data/womens-college-basketball) | Roster data for NCAA women's basketball, 2020–21 through 2025–26, with coach data |
| [soccer](https://github.com/Sports-Roster-Data/soccer) | Roster data for NCAA women's soccer programs |
| [lacrosse](https://github.com/Sports-Roster-Data/lacrosse) | Scrapers and data for NCAA men's and women's lacrosse, all three divisions |
| [field-hockey](https://github.com/Sports-Roster-Data/field-hockey) | Roster data for NCAA women's field hockey programs |
| [womens-volleyball](https://github.com/Sports-Roster-Data/womens-volleyball) | Roster data for NCAA women's volleyball programs |
| [utilities](https://github.com/Sports-Roster-Data/utilities) | Shared utility functions used across scrapers |
| [ncaa_stats_py](https://github.com/Sports-Roster-Data/ncaa_stats_py) | Fork of [armstjc/ncaa_stats_py](https://github.com/armstjc/ncaa_stats_py) for downloading and parsing NCAA data |

## Data

The women's basketball repository is the most developed. It includes season-by-season roster files going back to 2020–21, standardized fields for position, height, year, and hometown, and coach data. Other sports repositories are at earlier stages.

Across all sports, the scrapers pull data from team websites (primarily Sidearm Sports-powered sites) and export to CSV and JSON. Field coverage and data quality vary by sport and season, partly because team websites themselves vary considerably.

Known limitations and incomplete fields are documented in each repository's README.

## How It's Made

The scrapers are written in Python. Data cleaning and analysis work, particularly for women's basketball, uses R. Students in JOUR479X (Sports Data Analysis & Visualization) at the University of Maryland have contributed to the collection, cleaning and documentation.

## Use and Attribution

All repositories are licensed under MIT. If you use this data, please credit the Sports Roster Data Project at the University of Maryland.

We welcome corrections, bug reports, and pull requests. Use the Issues tab in the relevant repository to flag errors or ask questions.

## Contact

This project is supervised by [Derek Willis](https://github.com/dwillis), lecturer in data and computational journalism at the Philip Merrill College of Journalism, University of Maryland.
