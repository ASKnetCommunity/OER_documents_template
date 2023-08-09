# OER_documents_template

This repository is a template for creating documents in the environment of GitHub. It explains especially how to upload and link images into your document. Use this template repository for creating your own documents and repositories. 

For further information about GitHub visit: [ASKnet GitHub Guidance](https://asknet-open-training.github.io/Github-Guidance/)

**1. Choose the template repository**
   - Navigate to the repository `OER_documents_template`
   - Click on `Use this template`
   - Choose `Create a new repository`

     
![screenshot of choosing a template repository](/images/use_template.png)


**2. Create your repository**
  - Give your repository a meaningful name
  - Choose `Public` 
  - Click on `Create repository`

![screenshot of creating the repository](/images/create_repository.jpg)


**3. Create your document**
   - Give your document a meaningful name (see following image, first row, pink highlighted)
   - Write your document (by using markdown syntax)
   - Save your document by clicking on the green `Commit changes...` - button (see following image, first row, right side)
   - It is advisable to briefly describe in the text field for the `Commit message` (especially if you work in a collaborative environment) what you did.
   - click the green `Commit changes` - button


![screenshot of creating the repository](/images/create_document.png)


**4. Integragte images in your document**
   - Navigate to the `images`-folder
   - Click on `Add file` - dropdown
   - Choose `Upload files`


![screenshot of uploading an image(/images/upload_files.png)

   - Drag and drop your images on the intended area
   - the files for the upload will be displayed underneath that area
   - click the green `Commit changes` - button

![screenshot of uploading an image part 2](/images/upload_files_2.png)


   - Navigate back to your document
   - Navigate to the part of your text where the image should appear
   - Put in following line of code
     ```
     ![describing text for your image](/images/file_name.jpg)
     ```
     This code gives your image a descirbing alternative short text, or name (important in case the image cant be pictured), provides the path to where the image is saved (in the `images`-folder) and tells which one to choose (in case there are more than one images in the folder). Don't forget to choose the right filetype behind the `.`(png, jpg, etc.)


**Information about Markdown Language**

"Markdown is a lightweight markup language for creating formatted text using a plain-text editor. John Gruber created Markdown in 2004 as a markup language that is appealing to human readers in its source code form. Markdown is widely used in blogging, instant messaging, online forums, collaborative software, documentation pages, and readme files." (cited from [Wikipedia](https://en.wikipedia.org/wiki/Markdown))

This document is written by using markdown syntax. Clicking on the `Pen Icon` will open the Editing mode, which depict the markdown syntax.

For more informations about basic writing and formatting syntax please visit [GitHub: formatting syntax](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)

