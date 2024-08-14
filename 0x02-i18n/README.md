# 0x02. i18n

## Tasks
### 0. Basic Flask app
- First you will setup a basic Flask app in 0-app.py. Create a single / route and an index.html template that simply outputs “Welcome to Holberton” as page title (`<title>`) and “Hello world” as header (`<h1>`).

### 1. Basic Babel setup
- Install the Babel Flask extension:
```
pip3 install flask_babel
```
- Then instantiate the Babel object in your app. Store it in a module-level variable named babel.

### 2. Get locale from request
- Create a get_locale function with the babel.localeselector decorator. Use request.accept_languages to determine the best match with our supported languages.

### 3. Parametrize templates
- Use the _ or gettext function to parametrize your templates. Use the message IDs home_title and home_header.

### 4. Force locale with URL parameter
- In this task, you will implement a way to force a particular locale by passing the locale=fr parameter to your app’s URLs.

### 5. Mock logging in
- Creating a user login system is outside the scope of this project. To emulate a similar behavior, copy the following user table in 5-app.py.

### 6. Use user locale
- Change your get_locale function to use a user’s preferred local if it is supported.

### 7. Infer appropriate time zone
- Define a get_timezone function and use the babel.timezoneselector decorator.

###  8. Display the current time
- Based on the inferred time zone, display the current time on the home page in the default format. For example:
