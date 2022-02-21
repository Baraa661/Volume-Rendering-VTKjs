# CG-VTKjs
A Web GUI application

A volume rendering web app with VTK.js & HTML
● We used datasets provided in vtk examples (head for surface rendering and chest for ray casting)
● Features:
○ Support loading DICOM series dynamically using load button
○ Surface rendering with adjustable iso value (try sliders)
○ Ray casting rendering (with a fixed transfer function) :  ■ Adjustable transfer function.  ■ Shift preset.
○ An interactive widget to cut the volume in the three perpendicular planes vtkImageCroppingWidget

● vtkDICOMImageReader object is used.

# Head 
https://user-images.githubusercontent.com/61358818/154951698-f3449e16-8fe6-45e5-882d-36093e78049c.mp4

# Body
https://user-images.githubusercontent.com/61358818/154951780-1e3afa78-e075-40bf-a3a5-bf0bba87534d.mp4


