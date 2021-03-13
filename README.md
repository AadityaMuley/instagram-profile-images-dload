# Instagram Profile Images Downloader

### Python code which takes an Instagram profile URL as input and downloads all images to specified directory

### Requirements:

- Assuming you have python & Jupyter Notebook installed already on the system - if not just Google it its very easy and straightforward.
- Install pip for your operating system:
  -  ***for Ubuntu based Linux run the following commands on the terminal:***
  ```
      $ sudo apt update
      $ sudo apt install python3-pip  //installs for Python 3
      $ sudo apt install python-pip   //installs for Python 2
      $ pip3 --version  //check the installed version
      $ pip --version
  ```
  - ***for Windows:***
  - download the get-pip.py file from: https://bootstrap.pypa.io/get-pip.py
  - launch the cmd as administrator (right-click cmd and select run as administrator)
  - use cd command to navigate to the folder/directory containing get-pip.py file (tip: save it in downloads or any folder easily accsesible)
  - run commands:
  ```
      python get-pip.py
      check version: pip --version 
  ```
- Install beautifulsoup4 using the command:
```
    pip install beautifulsoup4
```
- Install requests module using the command:
```
    pip install requests
```
- Install selenium using the command:
```
    pip install selenium
```
- Three Chrome Driver files are included. Unzip the file according to your Operating System and add it to your system PATH. (Google the process of how to add chromedriver to path in your respective Operating System if you are unfamiliar with the process)
- Change the following in code before executing:
  - go to Google and search `my user agent` and copy the your user agent:
  - in the code go to the header variable and change the User-Agent to the one you got from Google
  - change the DRIVER_PATH to your own path where chromedriver PATH is stored
  - in your browser open any instagram image and inspect the image. Copy the class name of the div where images are located and change the img_links2 class name in the code to the class name you see on your browser
- ***Run the the code on Jupyter Notebook***
