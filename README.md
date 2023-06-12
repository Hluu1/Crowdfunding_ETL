# Crowdfunding_ETL

For the ETL mini project, I practiced building an ETL pipeline using Python, Pandas, and either Python dictionary methods or regular expressions to extract and transform the data. After transforming the data, Icreated four CSV files and using the CSV file data, I created an ERD and a table schema. At the end, I uploaded the CSV file datas into a Postgres database. All the coding I have done can be viewed in the Jupyter file named, "ETL_Mini_Project_TLUU.ipynb".

In the first part, I was tasked with importing the data from "crowdfunding.xlsx" and extracting its data. Once extracted, I then went ahead to clean the data and was tasked to create the Category and Subcategory DataFrames from the data and then, had to export said data as a CSV file. The result is showed down below. The images displays the two dataframes I have created and then exported which, can also be found in the resources folder named, "category.csv" and "subcategory.csv".

![Categorydata](https://github.com/Hluu1/Crowdfunding_ETL/assets/125692186/dae2a96e-1673-4d0f-bcdc-631290fd3baa)    ![subcategory](https://github.com/Hluu1/Crowdfunding_ETL/assets/125692186/203304e1-b390-45b3-900a-96ae15934591)
 



Then with the same data, I was then tasked with making another dataframe called Campaign. This is involved me doing some data cleanup and changing the data types to prepare the data to be ready for analysis. The following image displays the dataframe I have created. This can also be found in the resources folder named, "campaign.csv".

![campaign](https://github.com/Hluu1/Crowdfunding_ETL/assets/125692186/89f3f8b0-4231-488e-9336-8f9d2fe9683c)



Then for the next part, I was tasked with using data from the file, "contacts.xlsx", in the resource folder, to create another dataframe named "contact". However, for this section I was given two option to do this. The first option was to use Python Dictionaries to clean and sort the data and converting said data into a CSV file. The second option was the same except I was to use regular expressions instead. I opted for the second option as I wasnted to challenge myself as at this time, Regular Expressions was a new concept to me and I wanted to get more practice on it.

Before cleaning out the data, what someone was to see from the data is shown in the followig image.

![beforecleaning](https://github.com/Hluu1/Crowdfunding_ETL/assets/125692186/858bcd9a-b22d-4287-b539-82482744414a)


Then after using regular expressions, I was able to dissect the data and clean it. This ultimately made the data looking a lot more fliuid and easy to read while additionally, making it ready for analysis.

![Cleaned](https://github.com/Hluu1/Crowdfunding_ETL/assets/125692186/491a903c-7867-4302-825a-a28c85aed121)


Then after all this was done, I then made and ERD Chart based on the four Data that I have created and exported as shown in the image below but can also be viewed by the image in this repository named, "Crowdfunding Database ERD".

![ERD12](https://github.com/Hluu1/Crowdfunding_ETL/assets/125692186/e801bc5e-c36e-4429-b383-a12373172875)

After making the ERD, I was then used it to make a Table Schema for each of the four Datas that was created in SQL. In this case I used the program, "pgadmin4" to do this. The schema I have made can be viewed in this repositroy named, "crowdfunding_db_schema.sql". The following images showen are the results of me successfully making and imported the data for each of the four CSV files.

![SQLcategory](https://github.com/Hluu1/Crowdfunding_ETL/assets/125692186/80a24c99-d573-471b-8a42-4462b44df28c)  ![SQLsubcategory](https://github.com/Hluu1/Crowdfunding_ETL/assets/125692186/1bfbbdfb-03ea-4752-98e0-d39fca5a525d)


