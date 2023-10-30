# **Email Analyser**
This tool is designed to quickly run analysis of outlook emails files by using the  API services for IP analysis and URL analysis. With a user-friendly interface, it simplifies the extraction of email headers, parsing URLS and Attachments found in the email.

## **Features:**

- Quick email header extraction and analysis.
- Originating IP extraction and analysis via IPQualityScore API.
- URL parsing and anlaysis via Virustotal API.
- Attachment preview (Only avaiable for images).
- Save choosen attachment/Zip all attachment.

Ensure that you have the necessary .NET Framework or .NET Core version installed as required by the project.

## **Usage**
1. Update the api key under settings with your own API keys from VirusTotal and IPQualityScore respectively.
2. Run the application, and input the .msg file you want to check.

### Known issues
If you run into problems with the application not being able to access the .msg file, it is possible 
outlook is still open. Close outlook via taskmanger and try again
