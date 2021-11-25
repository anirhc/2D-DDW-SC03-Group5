# Data Driven World - Bonus Project

## Group Members
SC03 Group 5
- Muhammad Zulfiqar Bin Bakar (1005023)
- Huang Xinyi (1005488)
- Harikrishnan Chalapathy Anirudh (1005501)
- Sharryl Seto Shau Ru (1005523)
- Long Nguyen Tan (1005637)

## Setup
#### Vocareum
If you use Vocareum terminal to run your Flask application, you can do so by running the `runflaskvoc.sh` script. Before running this script, make sure the `voc=True` is set true in the following line inside `mp_sort/app/__init__.py`.

```python
# set voc=False if you run on local computer
application.wsgi_app = PrefixMiddleware(application.wsgi_app, voc=True)
```

Now, make sure you are inside the `2D` folder  by using the `pwd` command. 

```shell
> pwd
```

Use `ls` to ensure that you see the `runflaskvoc.sh` in the current folder.

```shell
> ls
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

### Downloading Repository
Clone the project repository from Github. On your terminal or Git Bash, type the following:

```shell
$ git clone https://github.com/anirhc/2D-DDW-SC03-Group5.git
```

### Go to Downloads Folder

Once you have downloaded the repository, you can go to the repository and to the folder called `2D` for this project.

```shell
$ cd Downloads/2D
$ ls
```

The last command should output the following:

```shell
Readme.md		
application.py
requirements.txt
app
```

## Create Virtual Environment (Windows)

**You should open Anaconda Prompt to do the following steps.**

In the following steps, the Windows prompt will be represented by:
```shell
>
```
Go to the root folder `mp_sort`.
```shell
> cd %USERPROFILE%\fip_powerx_mini_projects\mp_sort
```
From the root folder, i.e. `mp_sort`, create virtual environment called `virtenv`.

```shell
$ python -m venv virtenv
```

A folder called `virtenv` will be created. Now, activate the virtual environment.
```shell
> virtenv\Scripts\activate
```

You should see the word `virtenv` in your prompt something like:
```shell
(virtenv) folder>
```

_To exit the virtual environment at the end of this mini project, simply type:_
```shell
> deactivate
```

## Create Virtual Environment (MacOS/Linux)


In the following steps, the MacOS/Linux prompt will be represented by:
```shell
$
```

Go to the root folder `mp_sort`. 
```shell
$ cd ~/fip_powerx_mini_projects/mp_sort
```

From the root folder, i.e. `mp_sort`, create virtual environment called `virtenv`.

```shell
$ python -m venv virtenv
```

A folder called `virtenv` will be created. Now, activate the virtual environment. 

```shell
$ source virtenv/bin/activate
```

You should see the word `virtenv` in your prompt something like:
```shell
(virtenv) user$
```

_To exit the virtual environment at the end of this mini project, simply type:_
```shell
$ deactivate
```
## Combined (Windows/Mac/Linux)

### Install Python Packages

Install the necessary packages for this mini project. From the root folder, i.e. `mp_sort`, type the following:

For Windows:
```shell
> pip install -U --force-reinstall -r requirements.txt
```

For MacOS/Linux: (For Linux, you might need to type pip3 instead)
```shell
$ pip install -U --force-reinstall -r requirements.txt
```

The above steps will install Flask and Transcrypt Python libraries and some other necessary packages.


 

#### Local Computer


If you are using your own computer, make sure to change the flag `voc=False` in the following line inside `mp_sort/app/__init__.py`.

```python
# set voc=False if you run on local computer
application.wsgi_app = PrefixMiddleware(application.wsgi_app, voc=False)
```

Now, you can run Flask by typing:

```shell
> flask run
```

You should see that some output will be thrown out, which one of them would be:

```shell
* Running on http://127.0.0.1:5000/ (Press CTRL+C to quit)
```


You can now open your browser at `http://127.0.0.1:5000/` to see the web app. You should see something like the following:

![](https://www.dropbox.com/s/a2fqx5svvyqtqf9/mp1_home.png?raw=1)

To stop the web app type `CTRL+C`. 


### Run Flask

Now you are ready to run your web app in your local computer. To do so, you need to go back to the root directory.

```shell
$ cd ~/Downloads/2D
```

Run Flask by typing:

```shell
$ flask run
```

You should see that some output will be thrown out, which one of them would be:

```shell
* Running on http://127.0.0.1:5000/ (Press CTRL+C to quit)
```

Now you can open your browser at `http://127.0.0.1:5000/` to see the web app. You should see something like the following:


To stop the web app type `CTRL+C`. 



### Expected Output

The expected output for both exercises 1 and 2 can be found in this video.

[Mini Project 1 Expected Output](https://youtu.be/4kDRFaUtiow)
