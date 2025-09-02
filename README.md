# n8n-Invoice-to-Gsuite

This workflow automates the process of handling invoice PDFs using **n8n**:

- **Trigger:** Simply drag and drop a PDF invoice into a designated local folder.  
- **Processing:** The workflow reads the file, extracts text, and parses billing information.  
- **Integration:**
  - Uploads the original PDF to Google Drive  
  - Logs the extracted details into a Google Sheet  
  - Performs a live currency conversion into THB  

The main challenge still being solved is how to automatically **organize uploaded files into dedicated client folders on Google Drive**, instead of one shared folder.

## Demo Video

https://github.com/Sungchunn/n8n-invoice-to-Gsuite/blob/main/images/ScreenRecording.mov
