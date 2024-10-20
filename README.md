## OBJECTIVE 
How to extract information from an invoice in image format (*.JPG) and from An image taken with a camera and saved in a PDF file (Scanned Image).
## TECHNICAL REQUIREMENTS
1)  [Load Image](https://docs.uipath.com/activities/other/latest/ui-automation%22/load-image)
2)  ### OCR Activities
    * [Tesseract OCR](https://docs.uipath.com/activities/other/latest/ui-automation%22/google-ocr)
    * [Get OCR Text](https://docs.uipath.com/activities/other/latest/ui-automation/get-ocr-text)
## PROCEDURES
### JPG
1) Load Image> browse your image
 

   ![image](https://github.com/user-attachments/assets/458324fd-3404-4bbb-a5cb-9ecca3558821)


2) In properties panel save the output variable

   ![image](https://github.com/user-attachments/assets/6331aba5-5b05-410d-b95f-6efce5b14bd9)

   * The type of the variable is UiPath.Core.Image

    <img src="https://github.com/user-attachments/assets/fd2e32e5-7719-4c7a-b572-254d42b28bf7" width="400">

 3) Use Tesseract OCR > Properties Panel > call an Image variable inside image box > save a variable inside Text box



    ![image](https://github.com/user-attachments/assets/5a801033-cdd6-4e1d-b63d-0a7d31627fac)



    .
   ![image](https://github.com/user-attachments/assets/c524830b-a716-4a80-b44b-94e785c8f01d)

 4) Message Box to print the Extracted data

 ### Scanned Image

  1) New Sequance > Use Application: Invoice Pic.pdf > Keyboard Shortcuts (CTRL+0)

    <img src="https://github.com/user-attachments/assets/5bcc2e89-372c-4e66-a29d-7ccdfa6e8d7d" width="400">

    
  2) Get OCR Text > Select the specific text

     ![image](https://github.com/user-attachments/assets/529c69cb-2383-4448-8d62-a629a3905edb)

  3) Store the extracted variable in through properties panel > Text box


      ![image](https://github.com/user-attachments/assets/f88aea00-1139-4cc9-914b-49d1c65b649a)


    
## Results

 To watch  Bot run this video, [click here](https://drive.google.com/file/d/1CXyYf139-sgbnP9pxZsrE7DV0nsG8inK/view?usp=drive_link)
