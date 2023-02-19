# Project
A project source code using bootstrap5 and custom css.


## Clone
Clone this repository to your local machine or simply fork this repository and open in codespace.

## Changing Colors
main colors are define in 'signin.css' file in 'root' section.

``` css 
:root
{
    --bg-color: #ffffff;
    --border-color: #eaeef5;
    --primary-color: #664de5;
    --secondary-color: #5c43e5;
    --white-color: #ffffff;
    --link-color: #0080ff;
    --text-color: #212529;
}
```
```
'primary-color' is main color of UI in our case it is purple.
```
```
'secondary-color' is the hover state color of all UI componenets such as 'button', 'input fields' etc.
```

## Web Structure
     Project
        |
        |/assests
        |   /Icons and images.
        |/css
        |   /bootstrap.min.css (bootstrap core css)
        |   /dashboard.css (dashboard css)
        |   /materialdesignicons.min.css (font icon css)
        |/fonts
        |   /material design fonts
        |/js
        |   /bootstrap.bundle.min.js
        |
        |-dashboard.html
        |-emp_form.html
        |-login.html
        |-signup.html


## CSS Framework
```
    1. form-container:
        container class, centering in the body.
    2. lineEdit
        input class (text/email/password/tel)
    3. passwordEdit
        input class (password and password retype fields.)
    4. login-btn
        primary button class.
    5. link
        link class (underline text and blue color)
    6. menu-dropdown
        select class (dropdown menu)
```

## Todo
1. Create the Dashboard front end.
2. Link all the pages together.
3. Update any necessary changes.
4. Develop backend.