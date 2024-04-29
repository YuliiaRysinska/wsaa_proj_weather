# wsaa_proj_weather
The main goal of the project is create a Web Application in Python using Flask which links with API from site https://home.
openweathermap.org/.


# Steps:
1) lanch and activate virtual machine and install packages and requirement file:
>python -m venv venv 
> .\venv\Scripts\activate
>pip install requests python-dotenv Flask 
>py -m pip install -U pip 
>pip freeze > requirements.txt

2) creating git ignore file to hide ".venv", ".env"
3) register on https://home.openweathermap.org and put api_key  to ".env" file
4) create css code  in  "static folder"
5) create html code in  "templates folder"
6) creating weather function in "weather.py" file
7) lunch Flask with code in "server.py"
8) setting production mode: pip install waitress -> pip freeze > requirements.txt
9) creating "weather.py" to get API
10) lunch app in browser
10) deploy to the web app to Zi: 

