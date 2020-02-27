1. run zip_to_df.ipynb 
	this will pull the Zipcode from Google maps API and create file 311_with_zip.CSV with the 311 data

2. run get_census_merg_311.ipynb
	this will crete the final file "final_311_census.csv"  by adding Census data and appending the 311_with_zip.CSV
	on initial run you will need to add a column names"CREATE_DATE" and substring the "CREATED_ON" date so it is in a YYYY-MM format

3. run line_chart.ipynb this creates Line charts for Presentation

4. run scatter_chart.ipynb this creates the scatter charts for presentation

5. run Google_Maps.ipynb this creates the heat map and plots the locations of incidents on google maps
!!! Note that if you run line 17 it will consume most if not all resoures on your computer
!!! and takes about 1 hr to render

6. run pieandbarcharts.ipynb this creates Pie charts for presentation

Final presentation is marked with file 311 Data analysis_final.ppt
