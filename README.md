<!-- Welcome to Your Project and Follow the Guidelines -->

<p align="center">
  <a href="https://osidigital.com/" target="_blank"><img src="images/readme_pics/osi.png" alt="OSI_Digital" width="100%" height="100%" /></a>
</p>


# <span style="color:orange">**Guidelines:**</span>
**_To set up Project Configurations follow the guidelines:_**
#

### <span style="color:blue">1.Cloning the Project</span>
### <span style="color:blue">2.Setting Up a Virtual Environment</span>
### <span style="color:blue">3.Activating the Virtual Environment (Windows)</span>
### <span style="color:blue">4.Navigating to the Backend:</span>
### <span style="color:blue">5.Installing Requirements:</span>
### <span style="color:blue">6.Installing Poppler for Windows</span>
### <span style="color:blue">7.Loading the .env File:</span>
### <span style="color:blue">8.Running the Project</span>

#

##  <span style="color:green">**Cloning the Project:**</span>


**To clone this project, use the following command:**

```
git clone https://github.com/srikanthstorm/onescan-services.git
```

## <span style="color:green">**Setting Up a Virtual Environment:**</span>

**To work with this project, it's recommended to use a virtual environment. If you haven't already, install virtualenv using:**

```
pip install virtualenv
```

**Create a virtual environment by running:**

```
virtualenv <virtualenv_name>
```

## <span style="color:green">**Activating the Virtual Environment (Windows):**</span>

**To activate the virtual environment on Windows, use this command:**

```
<virtualenv_name>\Scripts\activate
```

## <span style="color:green">**Navigating to the Backend:**</span>

**Navigate to the project's `Backend` folder.**

## <span style="color:green">**Installing Requirements:**</span>

**Use the following command to install project requirements:**

```
pip install -r requirements.txt
```

## <span style="color:green">**Installing Poppler for Windows:**</span>

**To install Poppler, follow these steps:**

- Download Poppler from the following URL:
```
https://github.com/oschwartz10612/poppler-windows/releases/tag/v23.08.0-0
```
<p align="center">
  <img src="images/readme_pics/poppler.png" alt="poppler" width="100%" height="100%" />
</p>

- Click `Release 23.08.0-0.zip` to download the zip file.
- Extract the zip file to `C:\Program Files\`.

<p align="center">
  <img src="images/readme_pics/extract_poppler.png" alt="extract_poppler" width="100%" height="100%" />
</p>

- Edit the Environment variables and add the following path to System variables:
```
C:\Program Files\poppler\poppler-23.08.0\Library\bin
```

## <span style="color:green">**Loading the .env File:**</span>

<p align="center">
  <img src="images/readme_pics/env.png" alt="env" width="100%" height="100%" />
</p>

**Load the `.env` file into the Backend Directory to ensure the proper functioning of your project.**


## <span style="color:green">**Running the Project:**</span>

**Run the following command to start the project:**

```
python wsgi.py
```

**Then, open a web browser and navigate to the following address:**

```
http://localhost:5000
```

**This will allow you to access the project via your web browser.**

<span style="color:orange">**Now, you're ready to dive into your project! Enjoy coding!**</span>

