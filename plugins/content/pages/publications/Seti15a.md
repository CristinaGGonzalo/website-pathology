title: Automatic detection of large pulmonary solid nodules in thoracic CT images

## Arnaud A. A. Setio and Colin Jacobs and Jaap Gelderblom and Bram van Ginneken
MP

<a href="https://doi.org/10.1118/1.4929562">DOI</a>

## Abstract
Current computer-aided detection (CAD) systems for pulmonary nodules in computed tomography (CT) scans have a good performance for relatively small nodules, but often fail to detect the much rarer larger nodules, which are more likely to be cancerous. We present a novel CAD system specifically designed to detect solid nodules larger than 10 mm.The proposed detection pipeline is initiated by a three-dimensional lung segmentation algorithm optimized to include large nodules attached to the pleural wall via morphological processing. An additional preprocessing is used to mask out structures outside the pleural space to ensure that pleural and parenchymal nodules have a similar appearance. Next, nodule candidates are obtained via a multistage process of thresholding and morphological operations, to detect both larger and smaller candidates. After segmenting each candidate, a set of 24 features based on intensity, shape, blobness, and spatial context are computed. A radial basis support vector machine (SVM) classifier was used to classify nodule candidates, and performance was evaluated using ten-fold cross-validation on the full publicly available lung image database consortium database.The proposed CAD system reaches a sensitivity of 98.3% (234/238) and 94.1% (224/238) large nodules at an average of 4.0 and 1.0 false positives/scan, respectively.The authors conclude that the proposed dedicated CAD system for large pulmonary nodules can identify the vast majority of highly suspicious lesions in thoracic CT scans with a small number of false positives.

A <b>pdf file</b> of this publication is available for personal use.Enter your e-mail address in the box below and press the button. You will receive an e-mail message with a link to the pdf file.
<form action="sender.php">  <input type="text" name="email">  <input type="submit" value="Send Seti15a.pdf:pdfSeti15a.pdf:PDF by e-mail"></form>