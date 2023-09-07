# DataPipeline_AudioBooks

This project focuses on cleaning and transforming a dataset related to audiobooks. The primary objective is to preprocess the data to make it suitable for analysis and export it as a clean CSV file.

## Tasks

The following tasks are performed in this data pipeline:

1. **Clean Author Names**
   - Remove "Written by" prefix from author names.
   - Add a space between the first name and the surname (look for the capital letter).

2. **Clean Narrator Names**
   - Clean and format narrator names as required, similar to author names.

3. **Create a 'Minutes' Field**
   - Calculate and add a new field called "minutes" that represents the length of the audiobook in minutes.

4. **Ensure Release Date is a Date**
   - Validate and format the release date field to ensure it contains valid date values.

5. **Create a 'Rating' Field**
   - Calculate and add a new field called "rating" that contains floating-point values representing the audiobook's rating.

6. **Create a 'Number of Ratings' Field**
   - Calculate and add a new field called "number_of_ratings" that contains integer values indicating the number of ratings the audiobook has received.

7. **Convert Price to Float**
   - Transform the price column to ensure it contains floating-point values.

8. **Export Cleaned Data**
   - Export the cleaned dataset as a CSV file named "project_dataset_clean.csv."


