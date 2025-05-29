# INFOMHCML_AlDrLeWa
The project of Human-Centered Machine Learning

Be aware that folktables automatically downloads large data files to your local machine when executing
```
data_source_2023 = ACSDataSource(survey_year='2023', horizon='1-Year', survey='person')
ca_data_2023 = data_source_2023.get_data(states=["CA"], download=True) # California
```
for specific years (e.g., 2014, 2023). This can lead to errors during commit or push operations when using development tools like VS Code, due to the file size.
