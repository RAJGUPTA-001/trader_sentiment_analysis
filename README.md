# Quick setup using terminal(windows/VScode)  or Powershell   (not windows cmd) 
 Invoke-WebRequest "https://docs.google.com/uc?export=download&id=1DTACBNdVy5f_fi-NZR-_Bp2lCl8u2zqQ" -OutFile "desiredpath/notebook.ipynb"

 or directly using python 


 
import gdown

file_id = "1DTACBNdVy5f_fi-NZR-_Bp2lCl8u2zqQ"


gdown.download(f"https://drive.google.com/uc?id={file_id}", "desiredpath/notebook.ipynb", quiet=False)



Now just use RUN ALL  it will automatically download and make directories
