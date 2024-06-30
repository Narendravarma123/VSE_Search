

## Visual Search in E-Commerce




## Installation


Step:1

1.Clone this repository with the following command
```bash
  git clone https://github.com/Narendravarma123/VSE_Search.git
```

2.Make sure to have the python installed on your system and create a virtual environment.Follow the link 
```bash
https://python.land/virtual-environments/virtualenv
```
3.Thereafter install the requied dependncides
```bash
pip install -r requirements.txt
```
### Database setup


1.Install the xamp server

2.Run the port of apache and mysql

3.Go to localhost/phpmyadmin

4.Create a database with name 'menshut'

5.Upload the .sql which can be found in the database folder and export it 

```
Note:There will be the error showing that upload size have to be 40m 
```
## Screenshots

Step 1:- Open the XAMPP control panel and go to Apache Config button and open the PHP (php.ini) file in Notepad.

![App Screenshot](https://sp-ao.shortpixel.ai/client/to_webp,q_glossy,ret_img,w_714/https://www.myprograming.com/wp-content/uploads/2021/08/xampp-control-panel-1.jpg)

Step 2:Change post_max_size


![App Screenshot](https://sp-ao.shortpixel.ai/client/to_webp,q_glossy,ret_img,w_1024/https://www.myprograming.com/wp-content/uploads/2021/08/xampp-control-panel-2-1024x576.jpg)

Step:3:Change upload_max_filesize
![App Screenshot](![App Screenshot](https://sp-ao.shortpixel.ai/client/to_webp,q_glossy,ret_img,w_1024/https://www.myprograming.com/wp-content/uploads/2021/08/xampp-control-panel-2-1024x576.jpg))


Step:4:Change max_execution_time

![App Screenshot](![App Screenshot](https://sp-ao.shortpixel.ai/client/to_webp,q_glossy,ret_img,w_1024/https://www.myprograming.com/wp-content/uploads/2021/08/xampp-control-panel-4-1024x576.jpg))


step:5 Change max_input_time

![App Screenshot](![App Screenshot](https://sp-ao.shortpixel.ai/client/to_webp,q_glossy,ret_img,w_1024/https://www.myprograming.com/wp-content/uploads/2021/08/xampp-control-panel-5-1024x576.jpg))













## Model download
We have used the resnext50 model which was trained on 7000+ images on 8 categories and saved the model as .keras model 
```
Download the model from the github release and keep it in your project folder
```

Now Go to app.py
Find 
```
category_model = load_model(r'C:\Users\Ravindra Kanchu\Desktop\eco\eco\eco\resnet.keras')
``` 
Replace the model path with your downloaded model path




## Run Locally

Now you will have the required dependencies and the backend setup as well 

Go to the project directory

```bash
  cd 'your_project'
```


Start the server

```bash
  python app.py
```

Note:If you have any module_not_found error make sure to install them using the 
```
 pip install module_name
```




## Features

- Login/signup
- Visual search
- Orders page
- Interactive admin panel(add,view ,remove products)


## Screenshots

![App Screenshot](https://drive.google.com/file/d/1tG_m6_9UrF4OZTWnKCWcmv-zARJSZAZU/view?usp=drive_link)






