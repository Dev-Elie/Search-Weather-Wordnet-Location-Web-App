# Search,Weather,Wordnet and a Location Finder-Web-App
[![GitHub issues](https://img.shields.io/github/issues/Dev-Elie/Search-Weather-Wordnet-Location-Web-App)](https://github.com/Dev-Elie/Search-Weather-Wordnet-Location-Web-App/issues)
[![GitHub forks](https://img.shields.io/github/forks/Dev-Elie/Search-Weather-Wordnet-Location-Web-App)](https://github.com/Dev-Elie/Search-Weather-Wordnet-Location-Web-App/network)
[![Twitter](https://img.shields.io/twitter/url?style=social&url=https%3A%2F%2Ftwitter.com%2F)](https://twitter.com/intent/tweet?text=Wow:&url=https%3A%2F%2Fgithub.com%2FDev-Elie%2FSearch-Weather-Wordnet-Location-Web-App)

# Description
A all in one Search application,Weather finder,Wordnet Synonym/Antonym App and a Location finder application. Implemented using python Flask and MySQL. It consists of a 
search module where a user types in a keyword based on a previous selection,the response is a list of urls relevant to the keryword.Also included is a Weather ststus
module that returns a dictionary of a places weather status and location finder module that returns a place's geographical information.

**NB:** Commands issued are for a linux environment,however no one is limited.

# Installation
1. Create a new folder for the project and navigate into it
```
$ mkdir my_project
$ cd my_project
```
2.Inside the newly created folder create a virtual environment
```
 $ Python3.9 -m venv < env name>
```
3. Create another folder,name it "main",navigate to it and clone to it the applicatons files.
```
mkdir main
cd main
$ git clone https://github.com/Dev-Elie/Search-Weather-Wordnet-Location-Web-App.git
```
# Usage
1. Activate the virtual environment
```
$. venv/bin/activate
OR
$ source venv/bin/activate
``` 
2. Navigate into the "main" folder and install the requirements.
```
$ pip install -r requirements.txt
```
3. Use Migrate to create a new database
```
$ flask db init
$ flask db migrate -m "Initial migration."
$ flask db upgrade
```
4. Make the run file an executable
```
$ chmod 777 run
```
5. Launch the application
```
$ ./run
```
# Preview
![Home](https://github.com/Dev-Elie/Portfolio/blob/main/images/projects/slww.png
 "Q & A Page")

Liked this project ? 
Feel free to tweet about it [![Twitter](https://img.shields.io/twitter/url?style=social&url=https%3A%2F%2Ftwitter.com%2F)](https://twitter.com/intent/tweet?text=Wow:&url=https%3A%2F%2Fgithub.com%2FDev-Elie%2FSearch-Weather-Wordnet-Location-Web-App)
