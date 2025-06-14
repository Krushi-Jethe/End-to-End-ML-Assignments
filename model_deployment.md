# Model deployment 


The aim of this assignment is to **familiarize yourself with model deployment**. Here you will learn to containerize your application for deployment.

<br>

### ⚡FASTAPI 

- [ ] Write a script which accepts requests, loads models and returns predictions for the requests.

<br>      

### 🖥️	Streamlit App

- [ ] Write scripts for your streamlit app which can do the following:
  - [ ] Upload button which accepts json and csv.
  - [ ] Dropdown to select the model to use for prediction.
  - [ ] Once data is uploaded call the FASTAPI to run the model on data and obtain predictions.
  - [ ] Display the predictions.
  - [ ] Optional: Provide options for exploring your clean dataset - View tables/plots.
  - [ ] Use `streamlit run Home.py --server.port 5000` to display your app. (You can edit your code and view the changes simultaneously)

<br>      
     
### 🏗️ Docker

- [ ] First we will save the requirements by running the following command `pipreqs . --force`
- [ ] Now update the Dockerfile script.
- [ ] After updating the Dockerfile script run `docker build .` in terminal.
- [ ] Check your docker UI and check if the image has been created.
- [ ] Now use `docker run` command to run the container.
- [ ] Click on the URL and check if you are able to view and run the app.
