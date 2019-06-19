# Euro 2016
The data for the Euro 2016 competition consists of:
1. `data.txt` which contains the core data for the competition including matches, dates, teams, stages, groups, and stadia.
2. `links-1.txt` to `links-51.txt` each of which contains `(site, title, description, url)` for a collection of match reports. The numeric part of the filename matches the `id` of the match in `data.txt`. 

The `stages` property in `data.txt` contains all the match data inline and in a sensible order so it's an easy starting point for getting students to generate HTML from that data.

Other properties in `data.txt` could be useful for validating students' analysis of the main match data if you choose to have them derive that data from `matches` for example.

The data does not contain scores or match results except indirectly: a fun project might be to parse the `title` or `description` in the `links-X.txt` files to obtain the scores, or to look up the scores online some other way.
