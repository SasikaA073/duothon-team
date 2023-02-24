# Unity Pharmacy Hub Project

Funcionalities available so far in the site :
* User Signup
* User Login/Logout
* (Django Inbuilt user authentication)
* Password Reset ( Using Twillio as a service ) # Have to be implemented. 
* Drug inventory view
* Add drugs and edit them and edit them
* User Authorization features for pharmacies
  
This is how to get started and customize it.

   
1) First, clone the repository. 

        git clone https://github.com/SasikaA073/Social-blog

2) Then run this command to activate a python environment. After that activate the environment. 

    In linux,

        virtualenv --python=python3 ~/venv/MyVirtEnv
        source ~/venv/MyVirtEnv/bin/activate

    In Windows,

        python -m venv "MyVirtEnv"
        source MyVirtEnv\Scripts\activate
            
    If your Python virtual environment works fine, then in the command line should be something similar to this.
    


        (MyVirtEnv) C:\Users\Foo

3) Now you have to install the required python libraries. Then run this command.

        pip install -r requirements.txt

4) Now the last part!
   
        python manage.py runserver

 
        
        

