title: Automatic rib segmentation and labeling in computed tomography scans using a general framework for detection, recognition and segmentation of objects in volumetric data

## J. Staal and B. van Ginneken and M. A. Viergever
MIA

<a href="https://doi.org/10.1016/j.media.2006.10.001">DOI</a>

## Abstract
A system for automatic segmentation and labeling of the complete rib cage in chest CT scans is presented. The method uses a general framework for automatic detection, recognition and segmentation of objects in three-dimensional medical images. The framework consists of five stages: (1) detection of relevant image structures, (2) construction of image primitives, (3) classification of the primitives, (4) grouping and recognition of classified primitives and (5) full segmentation based on the obtained groups. For this application, first 1D ridges are extracted in 3D data. Then, primitives in the form of line elements are constructed from the ridge voxels. Next a classifier is trained to classify the primitives in foreground (ribs) and background. In the grouping stage centerlines are formed from the foreground primitives and rib numbers are assigned to the centerlines. In the final segmentation stage, the centerlines act as initialization for a seeded region growing algorithm. The method is tested on 20 CT-scans. Of the primitives, 97.5% is classified correctly (sensitivity is 96.8%, specificity is 97.8%). After grouping, 98.4% of the ribs are recognized. The final segmentation is qualitatively evaluated and is very accurate for over 80% of all ribs, with slight errors otherwise.

A <b>pdf file</b> of this publication is available for personal use.Enter your e-mail address in the box below and press the button. You will receive an e-mail message with a link to the pdf file.
<form action="sender.php">  <input type="text" name="email">  <input type="submit" value="Send Staa07.pdf:pdfStaa07.pdf:PDF by e-mail"></form>