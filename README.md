
![header](https://user-images.githubusercontent.com/37442807/229185900-602d35e1-32e5-4953-8e74-3052a42ff419.png)


<h1 align="center"> SafeLane. </h1>

<p align="center">SafeLane. - Your Road Safety Companion <br> Safelane. is designed to tackle neglected issue of potholes, open manholes, and other road hazards that can lead to accidents.

### Project Info
The contents in this project follow the following structure, where all views are containerised into screens.

```
├───models
|
├───screens
│   ├───OnBoarding
│   ├───Auth
│   ├───Home
│   ├───Map
│   ├───Contribute
│   ├───My contributions
│   └───Profile

```

### Description
 -  This app is Flutter based mobile app. I wanted
    a application to be a cross-platform application, that's why we picked flutter as our
   framework.
  
 - For the backend, we mostly relied on Firebase, as it was easier to
   integrate with the flutter app, without any hassle to manage & create
   instances of our server. 
 - For sign-up & authentication, we used Firebase auth. 
 - For storing the different types of data including user data, posts, etc. we chose Cloud Firestore because of its robust
   features and ability to query & filter out documents with ease.
 - Map is built using Google Maps API and Direction API is enabled in the Google Maps for polyline formation.
 - Deeplink is used to mail the details of road obstructions to concerned authorities.
 
 
 ------------------------------------
