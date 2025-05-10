Analyze Chicago Crime Dataset

The dataset includes crime incidents in Chicago from 2001 to 2022.
Data is sourced from the Chicago Police Department's CLEAR system.
Objective: Analyze crime trends and patterns to provide insights and recommendations for the City of Chicago.
Scope: Covers over 21 years of crime data, detailing locations, types, and time-based trends.
Challenges: Missing data, potential reporting biases, and data inconsistencies.

Source: City of Chicago Open Data Portal.
Records: 7.69M crime incidents over 21+ years.
Key Features: Crime type, location, date, arrest status.
Data Format: CSV file (~1.6GB), structured in 30 columns.

Rows & Columns: 7.69M records, 30 columns.
Key Data Types: Categorical (crime type, location), Numeric (district, year), Boolean (arrest, domestic case).
Missing Data: 614K+ missing in wards, 81K+ in coordinates.
Duplicates: No duplicate rows found.
First Look: Top crime types = Theft, Battery, Criminal Damage.

Dropped Columns: Wards, Zip Codes, FBI Code, Historical Boundaries.
Filled Missing: Location = "Unknown", District = "Unknown".
Converted: Date -> datetime, Crime Severity -> categorized.
Checked Duplicates: None found.
Memory Optimized: Reduced dataset size from 5.98 GB to 3.09 GB by removing unnecessary fields.

Time Features: Year, Month, Day, Hour, Weekend flag.
Crime Severity: High (Homicide, Assault), Medium (Burglary, Drugs), Low (Theft, Fraud).
Time of Day: Morning, Afternoon, Evening, Night.
Arrest Rate: Calculated per police district.
Geospatial Mapping: Crime heatmaps & community-based analysis.