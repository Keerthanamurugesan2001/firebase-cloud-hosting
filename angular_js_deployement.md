# Firebase

## Deploy: (Angular JS)

- Ensure package.json is updated up to date
- ```npm install```
- ```npm install -g firebase-tools```
- firebase login
- Firebase authorization.
- firebase init
- File name public or other name -> where all your files should exist 
- GitHub maybe yes or no
public/htm already exist? Overwrite? Always no

- Build (npm run build)
- Need GitHub authorization.
- Move the file to the public directory

- Build it (npm run build)
- firebase use <project-id>
- Project id is found in the setting of firebase.
- firebase deploy
- Ensure firebase.json created

```
{
 "hosting": {
   "public": "public",
   "ignore": [
   "firebase.json",
     "**/.*",
     "**/node_modules/**"
   ],
   "rewrites": [
     {
       "source": "**",
       "destination": "/index.html"
     }
   ]
  
 }
}
```

- Ensure .firebase folder create and hosting.cHVibGlj create
- And have all the files of your project listed there
- Ensure .firebaserc is created where your project id is has mapped

  
```
{
 "projects": {
   "default": "table-grid"
 }
}
```


**REf link:**

https://plainenglish.io/blog/how-to-free-deploy-the-static-html-website-in-firebase


