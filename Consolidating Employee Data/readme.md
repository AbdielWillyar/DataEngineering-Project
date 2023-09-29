In this project, we address the challenge of organizing and structuring human resources data for a small business experiencing rapid growth. As the first and sole data practitioner on the team, our mission is to create structured processes, guidelines, and standards for managing HR data efficiently.

The primary objective of this project is to centralize and standardize the scattered HR data, which currently exists in various formats, including Excel files, CSVs, and JSON files. We will explore and transform four key data sources:

1. **Office Addresses**: These addresses are stored in the "office_addresses.csv" file. We also identify remote employees where the "office" value is NaN.

2. **Employee Addresses**: Employee addresses are extracted from the "employee_information.xlsx" file.

3. **Employee Emergency Contacts**: This data is located in the "emergency_contacts" tab of the same "employee_information.xlsx" file. Note that the header information had been removed, and we've restored it to include fields such as employee ID, last name, first name, emergency contact details, and relationship.

4. **Employee Roles, Teams, and Salaries**: Extracted from the "employee_roles.json" file, this dataset provides information about employees' titles, monthly salaries, and their respective teams.

We use Python and Pandas to process, clean, and merge these datasets, resulting in a comprehensive and well-structured HR dataset.
