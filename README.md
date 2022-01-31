# MyPhoto
A simple photo sharing social networking application.<br />

## Backend made in python with [Django](https://www.djangoproject.com/)

#### Prerequisites
  - Make sure you have [python](https://www.python.org/) installed.

#### Clone & install

* Clone this repo
* `cd myphoto`
* Remove ".example" from ".env.example"
* Make sure to set your database information in .env
* Run `pip install -r requirements.txt`
* Run `python manage.py makemigrations`
* Run `python manage.py migrate`
* Run `python manage.py runserver` to start the server.

## Front end is built using [React native](https://reactnative.dev/)

#### Prerequisites
  - Make sure you have [nodejs](https://nodejs.org/en/) installed.
  - You can use npm to install Expo:
      ```
      npm install -g expo-cli
      ```

#### Clone & install

* Clone this repo
* `cd myphoto_react_native`
* Run `npm install`
* Mack sure to change the BASE_URL in 'myphoto_react_native/src/http/HttpRequest.jsx' to the url your backend is running on.
* Run `npm start`
* Press `i` to run in iOS simulator or press `a` for Android


## Preview
<p>
<img src="https://github.com/moSa963/MyPhoto/blob/master/preview.jpg" width="400" >
<img src="https://github.com/moSa963/MyPhoto/blob/master/preview1.jpg" width="400" >
<img src="https://github.com/moSa963/MyPhoto/blob/master/preview2.jpg" width="400" >
</p>

