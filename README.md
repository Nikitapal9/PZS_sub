# modelviewer

## Model preparation in PyMOL
•	Load and customize the model in PyMOL (2.4 or above!)

•	Avoid using mesh representation, and minimize sticks, balls and lines, as they will increase the file size. The file-size limit for GitHub is 25 MB.

•	Transparency and labels will not be applied in the model, but measurements will be visible, without values.

•	Set up the scene exactly as it is to be presented in 3D.

•	To generate the 3D object, use the command:' save filename.gltf ', or select ' File - Export image - GLTF... ' and save the 

## GitHub
For any issues with GitHub accounts, please visit the documentation of GitHub (https://docs.github.com/en)
1.	Create a GitHub profile if you don't have one
2.	Import the example repository (https://github.com/MokosDaniel/modelviewer) at the "+" button in the top right and name it (this name will be in the URL at the end)
3.	Upload your gltf model in your repository ('Add file' or just drag and drop it in the browser and commit changes)
4.	Edit the index.html file and change the name of the model "example.gltf" in line 4 to the name of the uploaded object, "filename.gltf"
5.	Commit changes, then in the repository, go to 'Settings - Pages - Branch' and select 'main' from the list (the repository has to be public for this to work)
6.	Save, and after a few minutes the link for the virtual 3D scene should show up in the Settings - Pages site.
