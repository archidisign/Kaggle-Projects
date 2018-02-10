## README
<br>
Competition link: <a href="https://www.kaggle.com/c/dstl-satellite-imagery-feature-detection">Link</a> <br>
Project by: archidisign, yzhang0 <br>
The data can be downloaded at the Kaggle competition link and were not reuploaded onto this Github repository. The Kernel we developped only uses satellite images in 3-band format (traditional RGB natural color images). Full data information can be found at <a href="https://www.kaggle.com/c/dstl-satellite-imagery-feature-detection/data">link</a>. <br>
"Three-band" dataset was stored in the folder "data" and training/grid_sizes csv files were stored in the folder "input". <br>
Modules needed in python:
<ul>
	<li>csv</li>
	<li>sys</li>
	<li>numpy</li>
	<li>pandas</li>
	<li>matplotlib</li>
	<li>shapely</li>
	<li>tiffile</li>
	<li>collections</li>
	<li>sklearn</li>
	<li>skimage</li>
</ul>
This project was done with the help of previous successful kernel from the competition. The following list of kernels were especially used to help us understand exactly how the image segementation was done.
<ul>
	<li><a href="https://www.kaggle.com/lopuhin/full-pipeline-demo-poly-pixels-ml-poly">Full pipeline demo: poly -> pixels -> ML -> poly</a></li>
	<li><a href="https://www.kaggle.com/torrinos/exploration-and-plotting?scriptVersionId=553107">Exploration and Plotting</a></li>
	<li><a href="https://www.kaggle.com/visoft/export-pixel-wise-mask/code">Export pixel-wise mask</a></li>
	<li><a href="https://www.kaggle.com/aamaia/trees-are-red-buildings-are-blue-sort-of">Trees are red, buildings are blue (sort of)</a></li>
	<li><a href="https://www.kaggle.com/c/dstl-satellite-imagery-feature-detection/kernels">All Kernels</a></li>
</ul>
Furthermore, a post explaining the science of semantic segmentation can be found on my blog <a href="https://catharticstudent.wordpress.com"> here </a>.
<br>
Tools: Python, Jupyter Notebooks
Keywords: Satellite, Kaggle Competition, DSTL, Python, Notebook, Learning
