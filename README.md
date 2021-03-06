# matheasy
Notepad with embedded calculator and HTML LaTeX output developed as part of my Bachelor's thesis at Faculty of Electrical Engineering, Sarajevo in 2013. Written entirely in C# using Windows Presentation Foundation.

Primary goal of this project was to embed useful and relatively powerful calculator inside ordinary plaintext document in a meaningful way.

# Screenshots
Main document editor:  

![ScreenShot](/Screenshots/Matheasy editor.png)  

HTML output preview using jqPlot and MathJax dependencies (not included in this repo)  

![ScreenShot](/Screenshots/Matheasy preview.png)

Autocomplete for special characters is triggered by typing in a backslash "\"
![ScreenShot](/Screenshots/Matheasy autocomplete.png)

For application to work, example .config file has to be located in the same folder as Matheasy executable. There also has to be a subfolder "Dependencies" with "jqPlot" and "MathJax" folders with respective JavaScript libraries if you want to preview HTML output on your computer. Webservice part (upload/download created files) is not included in this project.
