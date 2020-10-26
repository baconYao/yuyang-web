# yuyang-web

Link: [https://yuyang-web.web.app/](https://yuyang-web.web.app/)

## Deploy to firebase hosting

### Build production code
```
cd web
yarn build
```

### Deploy
```
mv web/build/* public
firebase deploy
```