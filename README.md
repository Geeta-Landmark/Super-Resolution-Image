# Super-Resolution-Image
 Machine Learning with Deep Neural Networks

----------------------------------------------------------------------------------------------------------
Created by
Geetanjali Sawant

----------------------------------------------------------------------------------------------------------
Dependencies:
	Python 3
	PyTorch >= 1.0 (CUDA version >= 7.5 if installing with CUDA)
	Python packages: pip install numpy opencv-python

----------------------------------------------------------------------------------------------------------
This project contain three folders: 

ESRGAN-EXISTING_MODEL
GSRM-OwN_Model
STREAMLIT_WEB_UI

In each folder you will find relevant README file to get output.
----------------------------------------------------------------------------------
GSRM-OWN Model
----------------------------------------------------------------------------------------------------------
Dependencies:
	Python 3
	Python packages: pip install numpy opencv-python

----------------------------------------------------------------------------------------------------------
For Testing Model:
----------------------------------------------------------------------------------------------------------
1) Using PyCharm:
	1. Copy 'GSRM_LR_IMAGES' folder in your current PyCharm project. 
	Place your own low-resolution images in 'GSRM_LR_IMAGES' folder which you want to test. 
	(There are five sample images in 'GSRM_LR_IMAGES' folder - Baby, Flower, Lemon, Nut and Nut_1).
	2. Make 'GSRM_SR_IMAGES' folder to see output images.
	3. Copy 'OWN_MODEL.h5' model in your current PyCharm project folder.
	4. Copy 'GSRM_OWN_MODEL.py'(for building model) and 'GSRM_OWN_TESTING.py'(for testing images) 
	in your current PyCharm project folder.
	5. Run 'GSRM_OWN_TESTING.py' file.
	6. You can see output images in 'GSRM_SR_IMAGES' folder.

----------------------------------------------------------------------------------------------------------
2) Using Google Colab: 
	1. Open 'https://drive.google.com/drive/folders/1iMSaZR28xMUHBdFp4eUR1twWp6oczkeT?usp=sharing' link.
	2. Download and unzip 'GSRM-OWN_Model' from above link and add it to your Google Drive.
	3. from google.colab import drive
	   drive.mount('/content/gdrive/')
	4. % cd gdrive/My Drive/folder_path
	5. cd GSRM-OWN_MODEL
	6. ! python GSRM_OWN_TESTING.py - Run this command in colab.
	7. You can see output images in 'GSRM_SR_IMAGES' folder.
-------------------------------------------------------------------
**ESRGAN Model**
Dependencies:
	Python 3
	PyTorch >= 1.0 (CUDA version >= 7.5 if installing with CUDA)
	Python packages: pip install numpy opencv-python

----------------------------------------------------------------------------------------------------------
For Testing Model:
----------------------------------------------------------------------------------------------------------
1) Using PyCharm:
	1. Copy 'LR' folder in your current PyCharm project. 
	Place your own low-resolution images in ./LR folder which you want to test. 
	(There are two sample images - baboon and comic).
	2. Copy 'figures' folder in your current PyCharm project.
	3. Copy 'models' folder in your current PyCharm project folder which contains 
	'RRDB_ESRGAN_x4.pth' model.
	4. Copy RRDBNet_arch.py, net_interp.py, transer_RRDB_models.py and test.py files 
	in your current PyCharm project folder.
	5. Run test.py file.
	6. You can see output images in 'results' folder.

----------------------------------------------------------------------------------------------------------
2) Using Google Colab: 
	1. from google.colab import drive
	   drive.mount('/content/gdrive/')
	2. % cd gdrive/My Drive/
	3. ! git clone https://github.com/xinntao/ESRGAN
	4. cd ESRGAN/
	5. Copy 'RRDB_ESRGAN_x4.pth' model in 'ESRGAN/models/' folder.
	6. ! python test.py - Run this command in colab.
	7. You can see output images in 'results' folder.
----------------------------------------------------------------------------------------------------------
Dependencies:
	Python 3
	PyTorch >= 1.0 (CUDA version >= 7.5 if installing with CUDA)
	Python packages: pip install numpy opencv-python

----------------------------------------------------------------------------------------------------------
---------------------------------------------------------------------------------------------------------------------------
Dependencies:
	Python 3
	Python packages: pip install numpy opencv-python

---------------------------------------------------------------------------------------------------------------------------
For Running:
---------------------------------------------------------------------------------------------------------------------------
Using PyCharm:
	1. Copy or make 'LR' and 'GSRM_LR_IMAGES' folders in your current PyCharm project. 
	2. Copy 'OWN_MODEL.PY' model in your current PyCharm project.
	3. In your current PyCharm project, make 'models' folder and Copy 'RRDB_ESRGAN_x4.pth' model inside it.
	4. Run 'streamlit run WEB_IMAGE_RESOLUTION.py' in your PyCharm terminal and the output will be displayed in the browser.
---------------------------------------------------------------------------------------------------------------------------
