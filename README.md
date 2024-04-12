Below are the steps for Installation and running the Flask server and Initiating the transaction with the Postman/Browser.

1. Make sure Python Installed in your system. If not Install the latest version of python using the below commands in terminal.

  First Run the below command
  /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"

  Second Install the Pyhton
  brew install python

  Check Installed Version
  python3 --version

2. Make sure Flask is Insatlled. If not use below commands in terminal to install Flask.

  syntax : python -m module <flaskname>

  -m venv tells the python to rum the module as script to create a virtual Environment.
  command: python3 -m venv my_flask_env
  
4. To activate the virtual environment use below command.
   
  source my_flask_env/bin/activate
  
5. Once the virtual environment is active, Install the flask using the below command.
   
  pip install Flask
  
6. After Installation of flask, check the version with below command.

  python -m flask --version
  
7. Install the flask requests in local (not in virtual env)

  pip install Flask reqexport FLASK_APP=app.pyuests
  
8. Run the Flask server using app.py file with below commands.

   export FLASK_APP=app.py

   set FLASK_APP=app.py

   flask run

9. Use postman/Browser to connect with blockchain using IP Address.

  http://127.0.0.1:5000
  
10. Used Postman/browser to get mine, create new transaction and get the chain.

    get mine - http://127.0.0.1:5000/mine

    create new - http://127.0.0.1:5000/transactions/new

    get chain - http://127.0.0.1:5000/chain


