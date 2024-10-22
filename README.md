# Illinois Hospital Report Card Data

This data is a snapshot of the data hosted at <https://healthcarereportcard.illinois.gov>. (Last Updated 2024-10-22)

There are three files:
 - [hospitals.csv](hospitals.csv): information about hospitals (key `entity_id`)
 - [measures.csv](measures.csv): metadata about the data measured for each hosptial (key `measure_id`)
 - [values.csv](values.csv): the values of each measure for each hospital during a particular date range (foreign keys `entity_id` and `measure_id`)
