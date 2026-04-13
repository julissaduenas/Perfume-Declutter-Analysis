# Perfume-Declutter-Analysis
## Project Overview
This project analyzes my personal perfume collection to better understand my fragrance preferences and reduce an overgrown collection. The goal is to identify signature scents by season, discover recurring fragrance notes, and build a data-driven approach to decluttering my collection.

Using R and SQL, I explore patterns in usage data logged daily alongside a master dataset of all owned fragrances.

## Goals
- Identify top perfumes worn all time and per season
- Discover my most frequently worn fragrance notes
- Understand personal scent preferences over time
- Support decluttering decisions (what to keep vs. remove)

## Dataset Description
### Master_List.csv
Contains all perfumes in my collection.

Key columns:

- ID – unique perfume identifier
- Brand – perfume brand
- Name – fragrance name
- Fragrance_Type – strength (eau de parfum, body spray, etc)
- Notes – fragrance notes
- Size – bottle size
- Price – retail price

### Daily_Log.csv
Tracks daily usage of perfumes.

Key columns:

- Date – date worn
- ID – perfume ID worn that day

## Workflow
### Data Cleaning (R)
Imported and standardized perfume dataset
Ensured consistent IDs across tables
Cleaned missing or inconsistent values
### Database Setup (SQL)
Created relational tables:
perfumes
notes
perfume_notes
Linked perfumes to fragrance notes
### Analysis
Aggregated daily wear data
Joined usage logs with master dataset
Created seasonal breakdowns
Identified most frequently worn perfumes and notes

## What's Next?
Continue to record data so all seasons are accounted for
I aim to create a declutter decision system to help me narrow down what to keep and what to not.
Since I do have the price listed, I curious about a cost per wear analysis
