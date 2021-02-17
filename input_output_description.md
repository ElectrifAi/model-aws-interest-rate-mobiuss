# Input/Output Description
- Input: 1 comma separated csv
- Details for each csv file:
    - interest_rate.csv (required)
        - Required columns:
            - month_tag: year month
            - IR: interest rate

    - Note: if end user do not have optional tables, empty CSV with identical columns should be generated to replace missing optional table.

	
- Output: a JSON list of objects contaning, for each record in the original order the following fields:
    - month_tag: year month
    - baseline: interest rates for Baseline scenario
    - optimistic: interest rates for Optimistic scenario
    - pessimistic: interest rates for Pessimistic scenario
 - Reference file: sample.csv.out
	
