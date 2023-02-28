# Bio-fluorography

<img src="https://github.com/devicons/devicon/blob/master/icons/python/python-original-wordmark.svg" title="HTML5" alt="HTML" width="40" height="40"/>&nbsp;
<img src="https://github.com/devicons/devicon/blob/master/icons/opencv/opencv-original-wordmark.svg" title="HTML5" alt="HTML" width="40" height="40"/>&nbsp;
<img src="https://github.com/devicons/devicon/blob/master/icons/numpy/numpy-original-wordmark.svg" title="HTML5" alt="HTML" width="40" height="40"/>&nbsp;
<img src="https://github.com/devicons/devicon/blob/master/icons/vscode/vscode-original-wordmark.svg" title="HTML5" alt="HTML" width="40" height="40"/>&nbsp;

The script that creates a .csv file with three fields:
* **image name**
* **category**
* **description**

Categories:
>**p (positive)** - dark colored bones \
>**n (negative)** - light colored bones

Description:
>**OK** - the image is in the correct folder \
>**!!! check !!!** - additional checking is required

Additional verification is required in the following cases:
* the image has very high/low brightness
* the spine is not in the center of the image


## **Getting Started:**

Clone the repository:

>*git clone git@github.com:airatns/bio-fluorography.git*

Set up the virtual environment:

>*python -m venv env* \
>*source env/scripts/activate*

Install dependencies in the app using requirements.txt:

>*python -m pip install --upgrade pip* \
>*pip install -r requirements.txt*

Put images in folders:

>**positive** \
>**negative**

Run the script:

>*python script.py*

The results will be in the file **result.csv**
