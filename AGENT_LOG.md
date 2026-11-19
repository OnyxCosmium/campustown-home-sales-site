# Agent log

Add a dated entry each time you work with your AI coding agent, with the newest entry at the bottom. Each entry records what you asked the agent, what it produced, and what you checked or changed. Paste your key prompts in exactly as you typed them. Include at least one time the agent got something wrong, and how you caught it.

Copy this outline for each entry:

```markdown
## YYYY-MM-DD: What you worked on

- **Asked:** "Paste your prompt here."
- **Agent produced:** What it made or changed.
- **Checked or changed:** How you checked it, and what you fixed.
```

```markdown
## 2026-11-18: Adding a City Median Price Range Table

- **Asked:** "Red AGENTS.md and docs/data_description_sheet.md first. Then replace the placeholder index.html with a page that shows the median sale price for each city, computed from data/college_town_home_sales.csv. Leave out sales under $10,000 and state that rule on the page."
- **Agent produced:** Copilot added a new page to my website, filtering the dataset to sale prices >= 10,000, grouped it by city and state, then calculated their medians.
- **Checked or changed:** No edits were made. This was to ensure that Copilot actually pushed changes to the website.
```

```markdown
## 2026-11-18: Adding Filter Bars

- **Asked:** "Read AGENTS.md and docs/data_description_sheet.md first. Our goal is to then add to index.html a new page that adds a dashboard based on the data found in data/college_town_home_sales.csv. First, work on the filter control bars. It should allow the user to view all 11 campuses at once or filter them up to one market location. It should also add a subtitle noting any data cleaning things the user applies."
- **Agent produced:** Copilot updated the page to have two dropdown selections - one which selected a campus and another which selected specific cities. Selecting a campus limited city selection options.
- **Checked or changed:** Changed the multiple choice selection to drop down menus for cleaner look on webpage and easier navigation.
```

```markdown
## 2026-11-18: Adding Summary Cards

- **Asked:** "Next, we want to work on adding high-level summary cards (KPI rows). They should line up across the top of the page and dynamically update based on the campus or city that the user selected. They should be based on the Median sale price, the total homes sold, the median price per square foot (or median square footage), and the most expensive vs. most affordable city. Each metric card should be stylized together as a unit, but each metric should have it's own card (four in total)."
- **Agent produced:** Copilot updated the page to have four summary cards for Median Sale Price, Total Homes Sold, Median Price/Sq.Ft, and Most Expensive vs. Most Affordable City.
- **Checked or changed:** Updated Most Expensive vs. Most Affordable City card to include Market Range.
```

```markdown
## 2026-11-18: Adding Main Grids

- **Asked:** "Next, we want to work on the main grid. This comes in three total elements.

The first is the campus price comparison, which should be a horizontal bar chart. It should rank all 11 universities or 18 cities from highest to lowest median sale price so that users can see immediately where Champaign-urbana sits in comparison to other college towns.

The second is the price trends over time, which should b e a line chart. This should show how median price sales have changed by year or season across the data set. This will help users quickly spot market spikes or cooling periods.

The third and last is the home size vs the sale price, which should be a scatter plot. This should plot the suqare footage against the sale price to show relationships between property size and cost, as well as quickly highlight outliers to the user."
- **Agent produced:** Copilot updated the page to have three different visualizations that displayed data based on the dropdown filter bars.
- **Checked or changed:** Nothing was changed for this one.
```

```markdown
## 2026-11-18: Updating the Table for Interactivity

- **Asked:** "The last step, the interactive data table, should be on the bottom section of the dashboard. It should be a searchable, sortable summary table that displays the key stats (sales count, median price, average bed/bath) for each of the 18 cities so users can inspect exact numbers instead of the summarized charts."
- **Agent produced:** Copilot updated the existing table to add a search bar. This would allow users to type in specific locations and have only city names that corresponded with what they typed appear on the table. This also added key stats for each city - sales count, median price, average bed/bath.
- **Checked or changed:** Nothing was changed for this one.
```
