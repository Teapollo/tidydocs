# Privacy Policy

**Last Updated:** October 2026  
**Developer:** Alan Nguyen | Contact: alannguyen1306@gmail.com

### 1. Plain-English Summary
TidyDocs is a 100% client-side Google Docs add-on. It runs entirely inside your browser session using Google Apps Script V8. We operate zero external database servers, collect zero personal data, and never transmit your document text across the internet.

### 2. Permissions & Data Usage
TidyDocs requests only the minimum permissions necessary to function:
* `documents.currentonly`: Used strictly to read and format text in the single active document currently open in front of you. It cannot access any other file in your Google Drive.
* `script.container.ui`: Used strictly to display the TidyDocs sidebar and settings interface inside Google Docs.

### 3. Data Storage & Retention
* **Zero Document Retention**: Your text is processed ephemerally in your browser's sandboxed memory during operations (sorting, cleaning, casing) and is never saved, cached, or logged.
* **Local Settings**: User preferences (such as your chosen sort order) are saved strictly in your local browser sandbox (`localStorage` / Google Apps Script `PropertiesService`).

### 4. Google Limited Use Disclosure
TidyDocs' use and transfer of information received from Google APIs adhere strictly to the [Google API Services User Data Policy](https://developers.google.com/terms/api-services-user-data-policy), including the Limited Use requirements. Document content is never transferred to third parties, never used for advertising, and never used to train machine learning models.

### 5. Contact
If you have any questions or feedback, contact Alan Nguyen at **alannguyen1306@gmail.com** or open an issue on GitHub.
