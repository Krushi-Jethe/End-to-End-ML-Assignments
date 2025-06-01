# LINUX: Writing Shell Scripts 


The aim of this assignment is to **familiarize yourself with essential Linux CLI commands** that are frequently used in development and scripting environments. You should experiment with the following commands to understand their purpose and usage:  

*Note: These are just a few commonly used commands. Feel free to explore and try out more as you learn.*

### 📂 Commands to Explore

- `cd`
- `ls`
- `mkdir`
- `rm`
- `touch`
- `cat`
- `wget`
- `unzip`

---

### ⚙️ Flags & Options to Try

Explore their basic functionality along with various useful flags/options, such as:

- `ls -a` : Show all files, including hidden ones
- `ls -l` : Long listing format
- `rm -rf` : Forcefully remove directories and their contents
- `mkdir -p` : Create nested directories


---
### 🎓 Assignment

- [ ] Write a shell script which does the following: 

  - [ ] Creates a directory structure as given below: 

              ml-project/ 
              
              ├── app/ 
              
              │   ├── pages/      
              
              │   ├── Home.py      
              
              ├── data/                    
              
              │   ├── raw/                  
              
              │   ├── processed/           
              
              ├── notebooks/               
              
              ├── src/                      
              
              │   ├── data/                
              
              │   ├── features/         
              
              │   ├── models/        
              
              │   ├── visualization/     
              
              │   └── utils/               
              
              ├── models/                         
              
              ├── tests/                    
              
              ├── Dockerfile                
              
              ├── requirements.txt          
              
              ├── setup.py                  
              
              ├── README.md            
              
              └── .gitignore   

   - [ ] Install anaconda in your WSL, create a conda environment named ml-project and install requirements.txt in the environment. 

 
- [ ] Write a shell script which downloads the data, unzip the file, rename it and pass it through a python script to process it and save it. After the script is run you should have two CSVs generated and stored under a folder – original and processed. 

 
