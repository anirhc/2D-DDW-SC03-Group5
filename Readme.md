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
Since we are using the  Vocareum terminal to run our Flask application, we can do so by running the `runflaskvoc.sh` script. Before running this script, we need to make sure the `voc=True` is set true in the following line inside `2D-DDW-SC03-Group5/app/__init__.py`.

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

### Downloading Repository
Clone the project repository from Github. On your terminal or Git Bash, type the following:

```shell
$ git clone https://github.com/anirhc/2D-DDW-SC03-Group5.git
```
