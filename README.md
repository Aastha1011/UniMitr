<div align="center">

# AgriAI Web Application

</div>

## About

<b>AgriAI</b> is a machine learning based we application build using React and Flask. AgriAI is used for recommending Crop and Fertilizers based on the soil features. The application used three accuractely predciting models to make the final predictions. The link for the python notebooks containing the implementation for the models are present in the <b><a href="#links">All Links</a></b> section of this Readme.<br/>

An API was built using Flask and was deployed on Heroku. This Flask API is used to get the recommendation made by the machine learning models in JSON format. The input data is sent as a POST request to the API to get the predicted information.<br/>

React JS was used to build the frontend part of the application. JS packages such as MaterialUI, Axios, react-router-dom were used for frontend part of the web application.<br/>


<br/>
<b>Note:</b> This API can be used in your Web Application or Mobile Application by just sending a POST request with the necessary input data to the above mentioned end points.

## Steps to run the React Application in local

1. Clone this repo.
2. Open command prompt in the following folder "React_Frontend/agri-ai"
3. Install all the npm packages

```
npm install
```

4. Start the application

```
npm start
```

The Application Runs on localhost:3000

## Steps to run the Flask API in local

1. Clone this repo
2. Open command prompt in "Flask_API"
3. Create a virtual environment

```
mkvirtualenv environment_name
```

4. Install all the packages

```
pip install -r requirements.txt
```

5. Run the app.py file

```
python app.py
```
<br/>

## Demo Of Web Application

<img src="./readme_assets/lappy_gif.gif" />

<div align="center">

Please do ⭐ this repo if you liked my work.

</div>
