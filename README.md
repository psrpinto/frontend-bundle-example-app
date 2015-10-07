# frontend-bundle-example-app
An example app that uses Symfony Standard and [frontend-bundle](https://github.com/regularjack/frontend-bundle).

### Clone
```
git clone git@github.com:regularjack/frontend-bundle-example-app.git
cd frontend-bundle-example-app
```

### Setup
```
composer install
npm install -g bower
npm install -g gulp
npm install
bower install
```

### Run
```
app/console server:start
gulp
```

The app will be available at http://127.0.0.1:8000, with livereload enabled.

Source assets are under [app/Resources](app/Resources).
Compiled assets are under `web/assets`.
