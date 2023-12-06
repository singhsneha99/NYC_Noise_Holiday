# NYC Noise Analysis Based on Holidays

This project analyzes New York City 311 noise complaint data to identify trends across boroughs and major holidays. The goal is understanding how festivals and events impact noise disruptions for residents.

## Data

The [311 complaint data](https://nycopendata.socrata.com/Social-Services/311-Service-Requests-from-2010-to-Present/erm2-nwe9) is obtained from the NYC Open Data portal as a CSV. It is preprocessed to focus on noise complaints and relevant metadata like borough, date, complaint type etc. 

Key data fields:

- `Complaint Type` - category of complaint (filtered to noise)
- `Borough` - NYC borough
- `Created Date` - date complaint was filed  
- `Descriptor` - short complaint reason description

## Analysis

Analysis uses Pandas and Seaborn in Jupyter Notebooks to:

- Aggregate noise complaints by hour, day, month over time 
- Compare weekday vs weekend trends
- Identify complaint rates across boroughs  
- Classify complaints into holiday vs non-holiday
- Plot grouped bar charts, line plots and count plots

Key findings:
- Manhattan has highest overall noise complaints
- Weekends have fewer noise issues than weekdays
- Thanksgiving generates most complaints relative to other US holidays


Requirements: 
- Python 3.6+
- Pandas
- Matplotlib
- Seaborn

## References
Let me know if any sections need additional detail!
