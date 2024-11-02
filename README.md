# CodeShare

- This code has no AI elements but it searches a folder for matching files based on suffix/prefix names and matches them.
- It normalizes every data value within a file by doing string normalizations, date formatings, number formatings like removing special characters or removing leading/trailing zeros etc.
- The code logs these transformations in a separate file for revision.
- It then creates a unique key for each row by combining all the data by a delimiter, and checks if there are duplicates within the file.
- If there are duplicates, it logs the duplicates in a separate file.
- After that, it compares the keys to see if the data matches between the matchig files.
- If not, it also logs the key that doesn't have a match.
