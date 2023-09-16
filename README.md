# module_11_challenge

My tutor Kourt supported me with the following code 
# Create an empty list
data_rows = []
# Loop through the scraped data to create a list of rows
for row in  data_table.find_all('tr',class_="data-row"):
    data_rows.append(row)  
# Create a Pandas DataFrame by using the list of rows and a list of the column names
mars_temperature_df = pd.DataFrame(mars_data, columns=headers)
