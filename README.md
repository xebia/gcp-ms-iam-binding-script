# gcp-ms-iam-binding-script
To simplify permission reviews, we created a bash script to generate a quick and thorough overview of IAM bindings/roles across the Google Cloud Platform. You can run this script using Google’s Cloud Shell.

Steps:
Open Google Cloud Shell and create a new .sh file (e.g., nano export_permissions.sh).
Edit the file and paste the code, replacing the placeholder with your actual Organization ID.
We’ve also included a function to exclude specific folder(s), replace the placeholder with the actual folder ID you want to exclude.
Make the script executable by running: chmod +x export_permissions.sh in the terminal.
Execute the script with ./export_permissions.sh and watch the magic unfold.
The resulting .csv file will be saved directly to your Cloud Shell.

Disclaimer:
Permissions are sensitive data. Always ensure you align with relevant stakeholders to determine who should have access to this information and where it should be shared.
