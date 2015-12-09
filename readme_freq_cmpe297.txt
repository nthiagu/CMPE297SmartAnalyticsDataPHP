
Created by Thiagarajan Natarajan , December 09,2015.
Created for : SHELF Suggestion.

Phase 3 Table : Multiple customers with same buying pattern on different products.


This table contains the computed information listing how many different customers have the same buying patterns across all the products they buy.

Query to get required information : 

select freq_grouped_items from reco_data.freq_table where freq_count = 3;

select freq_grouped_items from reco_data.freq_table where freq_count = 4;


