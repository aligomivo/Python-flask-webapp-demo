# Deploy a Hello word Python web app to Azure App Service 

This is the demo Flask application for the Azure Quickstart.

If you need an Azure account, you can [create one for free](https://azure.microsoft.com/en-us/free/).

##Useful commands :

###Part 1

**Go to the application folder:**

  ```
  cd Python-flask-webapp-demo
  ```

**Create a virtual environment for the app:**

   Windows : 

    ```
	py -m venv .venv
	.venv\scripts\activate
    ```

   macOS/Linux :

   ```

   ```

**Install the dependencies:**

  ```
  pip install -r requirements.txt
  ```

**Run the app:**

  ```
  flask run
  ```

###Part 2

**login to Azure**

   ```
   az login
   ```

   **Deploy a ZIP package to your web app**

   ```
   az webapp deploy --resource-group <group-name> --name <app-name> --src-path <zip-package-path>
   ```

