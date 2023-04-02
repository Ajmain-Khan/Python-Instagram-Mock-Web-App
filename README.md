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

![video](demo/appDemo.mp4)

### Login Page
![login](demo/login.png?raw=True)

### Profile Page
![profile](demo/profileView.png?raw=True)

### Upload Image Interface
![profile](demo/postInterface.png?raw=True)

### Capture Image Interface
![profile](demo/captureImage.png?raw=True)

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
