# Bio-fluorography

<img src="https://github.com/devicons/devicon/blob/master/icons/python/python-original-wordmark.svg" title="HTML5" alt="HTML" width="40" height="40"/>&nbsp;
<img src="https://github.com/devicons/devicon/blob/master/icons/opencv/opencv-original-wordmark.svg" title="HTML5" alt="HTML" width="40" height="40"/>&nbsp;
<img src="https://github.com/devicons/devicon/blob/master/icons/numpy/numpy-original-wordmark.svg" title="HTML5" alt="HTML" width="40" height="40"/>&nbsp;
<img src="https://github.com/devicons/devicon/blob/master/icons/vscode/vscode-original-wordmark.svg" title="HTML5" alt="HTML" width="40" height="40"/>&nbsp;

Скрипт, который создает csv-файл, в котором рядом с каждым изображением указана его категория, по первой букве папки, в которой данное изображение находится

>**p (positive)** - кости темного цвета \
>**n (negative)** - кости светлого цвета

Также реализована дополнительная проверка, в верной ли папке расположено изображение. 

>**OK** - папка выбрана верна \
>**!!! check !!!** - требуется дополнительная проверка

Необходимость дополнительной проверки возникает, если

> изображение имеет очень высокую/низкую яркость \
> позвоночник расположен на изображении не в центре

## **Как запустить скрипт:**

Клонировать репозиторий и перейти в него в командной строке:

>*git clone git@github.com:airatns/bio-fluorography.git*

Cоздать и активировать виртуальное окружение:

>*python -m venv env* \
>*source env/scripts/activate*

Установить зависимости из файла requirements.txt:

>*python -m pip install --upgrade pip* \
>*pip install -r requirements.txt*

Изображения разместить в папки 

>**positive** \
>**negative**

Запустить скрипт:

>*python script.py*

Результаты в файле **result.csv**
