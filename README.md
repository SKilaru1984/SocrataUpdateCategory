This is the Java API to update the category of datasets on Socrata portal using the Socrata Open Data API (SODA).
1) To update the category we we will need list of dataset ids,new category and the type of the dataset i.e tabular
   blob etc
   	 
2) All the requried dataset ids, categories and dataset types should be provide in a excel file.
	Note: A sample excel file is provided in the  src/test/resources

3) Prerequisites: For this program to run successfully 
	a)Socrata credential's should be updated in the NYCOpenDataIntegration.properties
		Note: Also make sure the log location is provided in log4j.properties 
				Location of the file: src/main/resources
	b) The location to the excep file should be updated
	 	Note: Also make sure the sheet name in the excel file and in the NYCOpenDataIntegration.properties file
	 		  match
	c) If proxy exists please provide the proxy details and set proxy.enabled to true. If no proxy exists
		then keep the current configuration.
	
	d) Apache Maven should be configured			
	