To add new language translations:

1) Create a new CSV file in this folder with the following name format:
  <lang code>@<display name>@<font size>.csv
  
  Ensure the file has a UTF8 formatting.
  For a list of valid language codes, refer to https://msdn.microsoft.com/en-us/library/windows/desktop/dd757512(v=vs.85).aspx
  
  Examples:
  
  en-us@English@1.0.csv
  es@Spanish@1.0.csv
  fr-ca@French (Canada)@1.0.csv
  
  
2) Copy all values from the English CSV over.

3) Don't change the very first row (column headers)

4) Leave the ID column, and translate the Value column. Note that some strings are parameterized (e.g. {0} and {1}). These parameters must appear in your translated string.

5) Give us feedback about any issues.

6) Be sure to back up your work! We can't (at this point) guarantee that Steam won't remove custom files.