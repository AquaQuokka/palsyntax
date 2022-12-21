# How to install Palsyntax.

## 1. Download the latest stable .zip file
## 2. Make sure that all of the following plugins are installed.

  #### - wheel
  #### - setuptools
  #### - twine
  
  
## 3. Extract the .zip file.
## 4. Open your IDE.
  
  ### - If you don't have an IDE, we suggest using these IDEs:
     
     #### - PyCharm Community
     #### - Visual Studio
     #### - Visual Studio Code (While VS Code is not an IDE, it still is a powerful tool.)
 
 ## 5. Open the root folder of Palsyntax in your IDE.
 ## 6. Display the contents of the folder "dist".
  
  - There should be a single file in the folder.
  - Delete it.
  
 ## 7. In your IDE terminal, change the directory of the Terminal to the root folder of Palsyntax. This happens automatically in most IDEs, but if it doesn't, it is important that you do this step.
 ## 8. Run the following command in your terminal:
  
  ### - $ python setup.py bdist_wheel
    
    - After running the command, a file will appear inside the folder "dist".
    - Right click on the file inside the folder, and press copy path.

## 9. Move back to your IDE terminal, and type in the following command:

  - $ pip install <copied path>
  
## 10. Wait for the module to install.

## 11. You are good to go!
