Veeva-TSF-YTD-Calc
==================

Zero out and re-calculate the TSF YTD Activity field  for current calendar year (can be run at any time in the year).  May experience long run time for high TSF volume due to call queries.

How to Run
--------------
Option 1. Run manually via the SFDC Developer Console:
database.executebatch(new VEEVA_PS_TSF_YTD_CALC (),200); 
	
Option 2. Schedule a nightly routine.
Setup > Develop > Apex Classes > Schedule Apex
