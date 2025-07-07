#  Macro Tracker Backend

```markdown



##  Project Structure


macro-tracker/
├── controllers/
│   ├── authController.js
│   ├── userController.js
│   └── diaryController.js
├── middleware/
│   └── authMiddleware.js
├── models/
│   ├── User.js
│   ├── Food.js
│   ├── DiaryEntry.js
│   └── WaterLog.js
├── routes/
│   ├── authRoutes.js
│   ├── userRoutes.js
│   └── diaryRoutes.js
├── .env
├── server.js
├── package.json
└── README.md

```

##  API Endpoints

###  Authentication

####  Register

```
POST /api/auth/register
```
![register](https://github.com/user-attachments/assets/558cfa8e-e654-47e2-b864-c230a46a4c42)




####  Login

```
POST /api/auth/login
```
![login](https://github.com/user-attachments/assets/63c83f5b-b884-4291-9e7e-bf5a7369fe28)


###  User

####  Get Profile
```
GET /api/user/profile
```
![dashboard page](https://github.com/user-attachments/assets/95492ae3-3c3d-428d-b580-db9fb57eae40)



####  Update Profile

```
PUT /api/user/profile
```
![updating calopries and protien intake](https://github.com/user-attachments/assets/4dcb7537-387f-41ea-bb67-0ce2ff9edc06)


###  Diary / Food Log

####  Log Food

```
POST /api/diary
```


![posting logs](https://github.com/user-attachments/assets/fffa2a9c-8b07-4ab0-82bd-8bf6a0dafc02)


#### Get Dashboard Summary

```
GET /api/diary/dashboard?date=2025-07-07
```


![foodlog on the given date](https://github.com/user-attachments/assets/cc10d607-1c8c-45ca-b7e0-7129b307e34c)

