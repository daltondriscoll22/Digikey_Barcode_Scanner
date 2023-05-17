# Digikey_Barcode_Scanner


Set up:

  Log into Digikey API portal and make sure you 
  are a part of the "WHOI OOI/CGSN Electronics Lab" Production team.
  
  In order to access the Digikey API you need a Client ID and Secret.
  In the production app "LOSOS Components", you will find both of these. 
  
  You must set up a virtual python environment to run the following software.
  To do so you must: 
  - Clone this repository to designated folder
  - Go into your terminal and cd to the folder
  - Use the commands:
  
              python3 -m venv venv
              source venv/bin/activate
              pip install -e .
              
  (You may need to install pip)
          
          

Authorization:

    The virtual environment will be set up 
    and ready for functionality.
    
    Use the command: 
    
          python -m Initialize.authorize
          
    You will then be prompted to insert the Client ID and Secret.
    
    After entering the ID and Secret, the Digikey Webpage will open. If you are not signed in you will need to 
    sign in now, otherwise you will need to give approval and click Allow.
    
    Once done, you will be given an OAuth token to enter into the terminal prompt.
   
   
   
    Scanning:
    
    After completing all steps outlined above you will be able to run:
           python examples/scan.py
    in the terminal and you are all set to scan!
    
    
    
    
    
    You may need to install python packages
    using commands:
    
    pip install xlsxwriter
    pip install openpyxl
    pip install pandas
                              
    
  
  
