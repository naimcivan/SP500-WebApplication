# SP500-WebApplication

FIRST OF ALL, This is the link for the app: https://sp500-web-app.herokuapp.com/


STREAMLIT
==============
-Create your own environment in your local machine in order not to impact the dependencies of libraries.
-Go to that environment in anaconda prompt.

In that environment:
  1) conda activate YOUR_ENVIRONMENT
  2) pip install streamlit
  3) cd Desktop (or it can be in another file, depends....)
  4) streamlit run YOUR_APP.py
  5) Then you will see a prompted localhost page. It means it is working properly.


**From this point, I will explain how to set up your cloud app in Heroku.**




FILES MUST HAVE
===============
**1)requirements.txt**
  - This file should include the libraries that you utilized while creating app.
  - FOR EX: streamlit==0.86.0
  - To learn these libraries' versions: Go to "anaconda prompt" then write "conda list". The output will be all libraries. Then find the libraries that you used. Save&Close

**2)runtime.txt**
  - To learn the version of python that you developed your app: Go to "anaconda prompt" then write "python --version".
  - FOR EX: python-3.7.9
  - Save&close

**3)setup.sh**
  - This file adjusts the server and port for your computer.
  
**4)Procfile**
  - This file sets and run the app.
  - FOR EX: web: sh setup.sh && streamlit run sp500-app.py (WRITE THE NAME OF YOUR APP FILE :)
  
**5)sp500-app.py**
  - This is your app file that you write the code.
  
