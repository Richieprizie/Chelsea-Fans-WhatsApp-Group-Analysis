# Chelsea Fans WhatsApp Group Analysis

## Outline

- [Introduction](#introduction)
- [Data Collection and Preparation](#data-collection-and-preparation)
- [Key Insights](#key-insights)
- [Conclusion](#conclusion)

## Introduction

The purpose of this analysis is to gain insights on the most active members, peak messaging times, and overall activity within the Chelsea Fans WhatsApp group from October 12, 2023, to July 17, 2024.

## Data Collection and Preparation

1. **Extracting the Chat**:
   - Extracted the WhatsApp chat text and opened it in Notepad.
   - Used "Find and Replace" to separate dates, times, users, and messages with semicolons.

2. **Loading into Excel**:
   - Opened the text file in Excel.
   - Used "Text to Columns" to split the data into different columns and formatted the date type.
   - Saved the file as an Excel workbook.

3. **Processing in Power Query**:
   - Opened the saved Excel file in Power Query.
   - Deleted unnecessary columns after splitting.
   - Merged two time columns into a single column and deleted the redundant third time column.
   - Changed the data type to "Time" and removed errors.
   - Renamed columns to "Date", "User", "Messages", and "Time" appropriately.

4. **Cleaning the Data in Excel**:
   - Used "Find and Replace" to remove unrecognized characters.
   - Filtered out blank entries.
   - Thoroughly cleaned the data to ensure accuracy.

5. **Visualizing in Power BI**:
   - Imported the cleaned data into Power BI.
   - Created a comprehensive dashboard to visualize key insights.

## Key Insights

1. **Messages by Members**:
   - **Top 5 Members**:
     - Zoumlally: 19.9K messages
     - @Ote: 14.0K messages
     - Horpizz: 13.8K messages
     - OSEMU: 8.5K messages
     - Richard: 6.1K messages

   - **Bottom 5 Members**:
     - DWAY: 5.4K messages
     - Abdulgafar: 4.3K messages
     - King Zoumlally: 2.1K messages
     - Chelsea: 1.9K messages
     - Ssai: 1.8K messages

2. **Messages by Months**:
   - The graph shows a significant increase in activity in the months of April and December, indicating peak engagement during these periods.

3. **Messages by Year**:
   - **2023**: 52.43K messages (68.3%)
   - **2024**: 24.33K messages (31.7%)

4. **Peak Messaging Time**:
   - The treemap illustrates the distribution of messages throughout the day, identifying peak messaging hours.

## Conclusion

The analysis provides  insights into the group's dynamics and engagement patterns. This information can be used to optimize communication strategies, schedule important announcements during peak times, and recognize the most active members.

## Dashboard

<img width="667" alt="Annotation 2024-07-20 102026" src="https://github.com/user-attachments/assets/b3d7172a-44ca-4723-8790-333dbd5ed17c">
