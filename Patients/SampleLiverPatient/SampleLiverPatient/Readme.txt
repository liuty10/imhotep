IMHOTEP Sample Patient
========================================

This dataset provides a sample patient for the IMHOTEP framework.
Its intention is only to show how to include your own data set. The 3D segmentations are very rudimentary and may not be complete or accurate.

Usage:
===============================
To use the Patient data, you need to create a "Patients" folder _next to_ the IMHOTEP Project folder and extract the SamplePatient folder into this folder.
For example:
C:\IMHOTEP\imhotep-master\	<- Project folder containing "Assets" etc.
C:\IMHOTEP\Patients\SampleLiverPatient\	<- Folder containing the patient data and this file
C:\IMHOTEP\Patients\AnotherPatient\	<- Another patient data set

Files:
===============================
Each patient folder should include the following:
- A meta.json file describing the components of the data set
- A .blend file which contains the segmented surfaces
- A mesh.json giving the name of the .blend file and the colors of the containing organs/objects.
- A DICOM folder containing one or more DICOM series.
- Note that the STL folder is not used by IMHOTEP. It contains the segmentations and is only included for reference.
- A views.json file (generated automatically when you configure views in the View Control toolbar)
- An annotations.json file (generated automatically when you create annotations using the Annotation Control tool)

License:
===============================
License of the original DICOM (CT) Data:
	Info\license.txt

License of the segmentation and the meta data:
	DICOM\license.txt
