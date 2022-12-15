# analysis-of-leads-in-the-sales-funnel-using-mongodb
dataset containing a list of past leads in the sales funnel of an IT Services company.

The dataset consists of the following fields

OPID - Opportunity ID (string)
 *Denotes the unique ID for each lead. Has the following structure: *Keyword* - *Number*
    -All 'Technical Business Solutions' leads start with 'TECH' keyword.
     For example, TECH-1918.
    -All 'ERP implementation Solutions' leads start with 'ERP' keyword. 
     For example, ERP-1162.

SV - Sales Velocity (numeric)

OS - Opportunity Size (numeric)

CRS - Client Revenue Size (string)
  *Denotes the type of Client Revenue Size that each of these leads deals with.  Are of 3 types-
    100K to 250K
    250K to 500K
    500K to 1M
Status - Whether the lead was converted or not (string) 
  *Has two levels - 'Won' and 'Loss'
