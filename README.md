## Live-Collage

## By mercyakuku  
  
# Description  
This is a Django web application that emulates the basic functionalities of the Instagram application like posting a picture, liking and commenting on it, sharing the image, following and unfollowing a user account, and updating a user profile.

  
##  Live Link  
 Click this link https://livecollageig.herokuapp.com/  to visit the site.
  
## Screenshots 
 <img src="https://user-images.githubusercontent.com/100420952/173181487-c2925c0b-49c8-4e2a-b8f2-6159841da6c0.png">

 <img src="https://user-images.githubusercontent.com/100420952/173181535-d446cb57-2d30-4704-a3a0-829c7817f400.png">
 
<img src="https://user-images.githubusercontent.com/100420952/173181569-3935a3f3-a474-4890-827c-dc055a26b6e3.png">

<img src="https://user-images.githubusercontent.com/100420952/173181625-b5d9ae1a-b520-439f-ba85-9e1d81e744f8.png">
 
## User Story  
  
* Sign in to the application to start using.
* Upload my pictures to the application.
* See my profile with all my pictures.
* Follow other users and see their pictures on my timeline.
* Like a picture and leave a comment on it. 
  

  
## Setup and Installation  
To get the project .......  
  
##### Cloning the repository:  
 ```bash 
 https://github.com/mercyakuku/Live-Collage.git
```
##### Navigate into the folder and install requirements  
 ```bash 
cd Live-Collage pip install -r requirements.txt 
```
##### Install and activate Virtual  
 ```bash 
- python3 -m venv virtual - source virtual/bin/activate  
```  
##### Install Dependencies  
 ```bash 
 pip install -r requirements.txt 
```  
 ##### Setup Database  
  SetUp your database User,Password, Host then make migrate  
 ```bash 
python manage.py makemigrations 
 ``` 
 Now Migrate  
 ```bash 
 python manage.py migrate 
```
##### Run the application  
 ```bash 
 python manage.py runserver 
``` 
##### Running the application  
 ```bash 
 python manage.py server 
```
##### Testing the application  
 ```bash 
 python manage.py test 
```
Open the application on your browser `127.0.0.1:8000`.  
  
  
## Technologies used  
  
* [Python3.8](https://www.python.org/)  
* [Django 4.0](https://docs.djangoproject.com/en/2.2/)  
* [Heroku](https://heroku.com)  
  
  
## Known Bugs  
* There are no known bugs currently but pull requests are allowed incase you spot a bug. 
  
## Contact Information   
If you have any question or contributions, please email me at [mercyakuku24@gmail.com]  
  
## License 
MIT License

Copyright (c) 2022 mercyakuku

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

Copyright &copy 2022 mercyakuku