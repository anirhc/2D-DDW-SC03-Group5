# Data Driven World - Bonus Project
In this project, we will predict the target value from the features entered by the user using multiple linear regression.

## Group Members
SC03 Group 5
- Muhammad Zulfiqar Bin Bakar (1005023)
- Huang Xinyi (1005488)
- Harikrishnan Chalapathy Anirudh (1005501)
- Sharryl Seto Shau Ru (1005523)
- Long Nguyen Tan (1005637)

## Setup
#### Vocareum
Since we are using the  Vocareum terminal to run our Flask application, we can do so by running the `runflaskvoc.sh` script. Before running this script, we need to make sure the `voc=True` is set to true in the following line inside `2D-DDW-SC03-Group5/app/__init__.py`.

```python
application.wsgi_app = PrefixMiddleware(application.wsgi_app, voc=True)
```

Use `cd` to navigate to the `2D-DDW-SC03-Group5` folder

```shell
> cd 2D-DDW-SC03-Group5
```

Now, make sure you are inside the `2D-DDW-SC03-Group5` folder by using the `pwd` command. 

```shell
> pwd
```

Make sure that the script is executable by running the following command. 

```shell
> chmod a+x ./runflaskvoc.sh
```
The above script is to change the file to be executable for all users, group and owner.

To run the script, type the following.

```shell
> ./runflaskvoc.sh
```

Once it is running, you can open another tab in your browser and type the following url: [`https://myserver.vocareum.com/`](https://myserver.vocareum.com/).

To stop the web app type `CTRL+C`. 

### Downloading Repository (Run locally)
Clone the project repository from Github. On your terminal or Git Bash, type the following:
```shell
$ git clone https://github.com/anirhc/2D-DDW-SC03-Group5.git
```

## Create Virtual Environment (MacOS/Linux)

Go to the root folder 2D-DDW-SC03-Group5.
```shell
$ cd ~/Downloads/2D-DDW-SC03-Group5
```
From the root folder, create virtual environment called virtenv.
```shell
$ python -m venv virtenv
```
A folder called virtenv will be created. Now, activate the virtual environment.

```shell
$ source virtenv/bin/activate
```
You should see the word virtenv in your prompt something like:

(virtenv) user$
To exit the virtual environment at the end of this project, simply type:
```shell
$ deactivate
```

## Create Virtual Environment (Windows)

Go to the root folder 2D-DDW-SC03-Group5.
```shell
> cd Downloads\2D-DDW-SC03-Group5
```
From the root folder, create virtual environment called virtenv.
```shell
> python -m venv virtenv
```
A folder called virtenv will be created. Now, activate the virtual environment.

```shell
> virtenv\Scripts\activate
```
You should see the word virtenv in your prompt something like:

(virtenv) folder>
To exit the virtual environment at the end of this project, simply type:
```shell
> deactivate
```

## Combined (Windows/Mac/Linux)
Install the necessary packages for this project. 
From the root folder 2D-DDW-SC03-Group5, type the following:

For Windows:
```shell
> python -m pip install -U --force-reinstall -r requirements.txt
```
For MacOS/Linux: (For Linux, you might need to type pip3 instead)
```shell
$ python -m pip install -U --force-reinstall -r requirements.txt
```
The above steps will install Flask and other necessary packages.

Once again make sure you are inside the `2D-DDW-SC03-Group5` folder by using the `pwd` command.
```shell
> pwd
```
If not, naviagte back to the 2D-DDW-SC03-Group5 folder.
You can now Run Flask by typing:
```shell
$ flask run
```
You should see that some output will be thrown out, which one of them would be:
```shell
* Running on http://127.0.0.1:5000/ (Press CTRL+C to quit)
```
Now you can open your browser at http://127.0.0.1:5000/ to see the web app.
