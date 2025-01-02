# Shopping

This project was completed for the HarvardX CS50 AI course in Python. It learns based off of shopper data and determines whether or not a given shopper will purchase an item by comparing its data to all of the data from previous shoppers. Some setup is required:


# Setup

In shopping.csv:
- Use any CSV editor
- The first row should contain every category of data for the shopper, also known as the "attributes," as well as a column for "revenue" -- either FALSE or TRUE
- The second row and beyond should contain the data for each shopper
- all rows for a given column should be the SAME data type (i.e. an "isWeekend" column should only have rows containing boolean values)

In shopping.py:
- Under the "load_data" class, edit everything inside of "currentEvidence.extend( (" (on line 72).
- Change each label (i.e. int(row[0])) to match the datatype of each column of "shopping.csv"
- For example, if the second column is a float indicating price: float(row[1]) # price (comment isn't necessary but helpful)
