# [2018 Spring] Web Programming Final - Fashion Ceiba
This project was developed by [Jackson Hsieh](https://github.com/hsiehjackson), [Cynthia Liu](https://github.com/CynthiaYLiu), and [Pierre Sue](https://github.com/PierreSue). You can view this project on the browser through the following link [Fashion-Ceiba](https://fashion-ceiba.herokuapp.com/) and see the demonstration video by opening [Demo-video](https://youtu.be/NDc-VVZYLH0).

![image](https://github.com/CynthiaYLiu/Fashion-Ceiba/blob/master/img/68747470733a2f2f692e696d6775722e636f6d2f733341593361752e6a7067.jpeg)

* Topic : (Group 03) Fashion Ceiba
* Enable users to upload course handout, to update private and public notes immediately, and to ask questions online.
* Team member：解正平(B04901020)、劉芸欣(B04901152)、蘇峯廣(B04901070)
* **Deployed Website** : https://fashion-ceiba.herokuapp.com/
* **Demo Video** : https://youtu.be/NDc-VVZYLH0

## How to run
```
$ From Github:
    * git clone https://github.com/hsiehjackson/fashion-ceiba
    * change the MONGODB link in ./fashion-ceiba/.env
    * npm install (./fashion-ceiba/)
    * npm run server (./fashion-ceiba/)  - port:4000
    * npm run client1 (./fashion-ceiba/) - port:3000
    * npm run client2 (./fashion-ceiba/) - port:3001
    * If you want to use teacher mode, just sign up with name/email/pwd = ADMIN

$ From Deployed Link:
    * open https://fashion-ceiba.herokuapp.com/login
    * and enjoy
```

## Functions
* **Login Interface** : log in or sign up
    * Teacher (name/email/pwd == ADMIN/ADMIN/ADMIN)
    * Students (others)
* **Ceiba Basic functions**
    * Course information
    * Teacher information
    * Bulletin board/calender
* **Course Handout PDF**
    * Upload PDF file (need to wait a wile)
    * Update student's private notes (instant)
    * View teacher's public notes (instant)
    * Delete notes in current page
* **Ask/Answer Questions(chat room)**
    * Show the number of unread messages
    * Students can ask questions online
    * Teacher can receive questions and answer immediately in class

## References
```
1. https://github.com/daisy3607/react-sketch
2. https://github.com/wojtekmaj/react-pdf
3. https://github.com/lykmapipo/mongoose-gridfs
```

## Dependencies
```
* mongodb/mongoose/mongoose-gridfs
* node.js
* express.js
* graphql-yoga
* react-apollo
* react-sketch
* react-pdf
* node-sass
* react.js
```

## Work Distribution

* 解正平 [Jackson Hsieh](https://github.com/hsiehjackson)
    * Authetication/Basic funcion/PDF uploading  -- web interface/front end/back end/database
    * Deploy on herokuapp

* 劉芸欣 [Cynthia Liu](https://github.com/CynthiaYLiu)
    * Sketchboard -- web interface/front end/back end/database
    * Demo video editing

* 蘇峯廣 [Pierre Sue](https://github.com/PierreSue)
    * Chatroom -- web interface/front end/back end/database
    * README

