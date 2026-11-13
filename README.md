# What-s_in_an_Avocado_Toast-A_Supply_Chain_Analysis
Conducted a supply chain analysis of the ingredients used in an avocado toast to gain an understanding of the complex supply chain involved

## Avocado Toast Supply Chain: Finding UK Ingredient Origins from Open Food Facts | Python, pandas

Analysed Open Food Facts data to find where the UK's avocado toast ingredients come from. For avocados, olive oil and sourdough, I filtered messy product records to the relevant category and identified the most common country of origin.

# CONTEXT
Avocado toast needs ingredients that travel long distances. The goal was to trace three of them to their source countries as a first step towards studying supply chains, for example how long ingredients spend at sea.

# MY ROLE
I did the data filtering, analysis and the reusable function.

# WHAT I DID
• Loaded tab-delimited product files and kept the 14 relevant columns
• Filtered rows to products whose category tags match a supplied list of relevant tags (for example fruits and fruit-based oils), by splitting the comma-separated tags into lists and checking for overlap
• Restricted to products sold in the United Kingdom, counted the origin tags and took the most frequent
• Cleaned the origin tags into readable country names (removing the language prefix and replacing hyphens with spaces)
• Wrapped the full process in one reusable function and applied it to olive oil and sourdough, instead of copying the avocado code

# RESULTS
• Avocado: Peru
• Olive oil: Greece
• Sourdough: United Kingdom

# TECH STACK
Python, pandas, string and list handling, lambda functions, user-defined functions
