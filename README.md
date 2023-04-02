# Python-Instagram-Mock-Web-App
A mockup of Instagram's core features in Python using Flask.

## Features
- Login/Registration
- Public/Private accounts
- Search bar, searching for user profiles
- Follow/Unfollow users (send requests to private pages)
- Explore Feed from users you follow
- Upload Image/Gif Posts
- Upload directly from camera
- Captions
- Like/Comment Interactions
- Persistency via SQLite database



## Demo

https://user-images.githubusercontent.com/71261373/229378221-1484b176-221a-4e94-be03-a2468942f660.mp4

### Views                             
|Login Page | Profile Page |
|   :---:   |     :---:    |
![login](demo/login.png?raw=True) | ![profile](demo/profileView.png?raw=True)

|Upload Image Interface | Capture Image Interface |
|   :---:   |     :---:    |
![post](demo/postInterface.png?raw=True)  | ![capture](demo/captureImage.png?raw=True) 

## Requirements
 - Flask
   - pip install flask
 - SQLAlchemy
   - pip install sqlalchemy

## Execution
```bash
python app.py
```

Open browser to `localhost:5000`
