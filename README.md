
# SocialX

Android News application

Google Auth

Email Password log In

FIREBASE AUTH 

Firebase comes with bunch features essential for every android app starting from authentication to hosting the app.

Below are the advantages using Firebase in general:

Super easy and quick to implement.

No server side configuration needed. No PHP Scripts and No Database Designs.

Realtime update without using GCM.

Autoscaling built-in

Can start for free (only need to start paying once we hit 50 connections)

Robust APIs for Javascript (including several frameworks like Angular), iOS, and Android

Built-in support for authentication services like Facebook, Google.

Declarative Security Rules model allows us to enforce read/write privileges and data validation throughout the tree



NEWS FETCHING FROM API

Volley Library used for fetching data from API  https://newsapi.org/

Glide Library for image  implementation  'com.github.bumptech.glide:glide:4.11.0'

Volley Library for fetching data from api  implementation 'com.android.volley:volley:1.1.1'
    
For opening link in browse  implementation "androidx.browser:browser:1.2.0"




## API Reference

#### Get all items

```http
 https://newsapi.org/
```

| Parameter | Type     | Description                |
| :-------- | :------- | :------------------------- |
| `api_key` | `string` | **Required**. 3addf684762b4ed0a3b83481fa844541 |

#### Get item

```http
  GET /api/items/${id}
```

| Parameter | Type     | Description                       |
| :-------- | :------- | :-------------------------------- |
| `id`      | `string` | **Required**. Id of item to fetch |

#### add(num1, num2)

Takes two numbers and returns the sum.


## Demo

Insert gif or link to demo

Log in screen : https://user-images.githubusercontent.com/70112790/156890529-3877e586-4434-4931-9fc5-88ebfdc5a241.jpeg

Sign Up Screen: https://user-images.githubusercontent.com/70112790/156890579-15e8fd61-5b88-47c9-bb45-f9a12915089d.jpeg

News Screen :https://user-images.githubusercontent.com/70112790/156890555-6aa9375e-4a8f-43f2-82a9-3a4f5564c88f.jpeg

Demo Video : https://drive.google.com/file/d/1luzNZEFgApVetBmkJMqXvRJMVuSp67TM/view?usp=sharing

## Authors

- [KOKADWARAkshay](https://github.com/KOKADWARAkshay)

