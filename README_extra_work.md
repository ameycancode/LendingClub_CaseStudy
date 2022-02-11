There was some cleanup done around emp_length and addr_state columns.

Employee Length NULL values were filled up with the help of earliest_cr_line column where
it was assumed that for NULL values, the date when the first loan was given to this person 
was his minimum employable date

Rows with wrong state information was identified by checking their state code and if these
codes present between standard range of zip codes of that state

This was done during our case study but we felt this might not needed. But we just want to
record our work around this and get comments on the same.

Thanks!
