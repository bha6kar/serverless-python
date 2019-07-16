# serverless-python 


To run the code in local, run like normal project in the local system and use the main.py file as the index file. To run we can use this command:

```sh
 python3 main.py
```
# Zappa 

To deploy the project into lambda create the zappa_settings.json by running the command:

```sh
zappa init
```

Configure all settings accordingly.

To deploy using zappa, run the command:

```sh
zappa deploy dev
```
>**NOTE:** This will deploy to the dev environment change the dev to desired environment.

After 1st time deployment no need to deploy again.

Use command to update:
```sh
zappa update dev
```

>**NOTE:** Zappa will deploy all the libraries inside the virtual environment of python version you use. So use separate virtual environment for all the project and install only the required libraries.
