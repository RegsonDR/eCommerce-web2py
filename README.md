# eCommerce

This is a demo ecommerce website created using [Web2py](http://www.web2py.com/), which can easily be adapted and modified to serve as an actual ecommerce website.  Web2py is a Model-View-Controller (MVC) framework, which meant both the the backend database, scripts and frontend HTML could be created from it. 

### Features
- User permissions.
- Pagination, searching, sorting (oldest, rating, alphabetically & price) & filtering (type & size).
- Product review system (rating, title, author, timestamp, body).
- Login (with recaptcha), registration (email verification), forget password (reset link sent to email).
- Admin interface (managing users, products & reviews) with tools to add, delete or edit. 
- Other features include Image carousels, similar products section, best sellers section, 404 pages & star-rating displays.

### Installation & Set Up 
The application needs to be stored in a unique directory in web2py's application directory. Once doing so, models/db.py (lines 99:103) must be modified with valid email credentials, to allow the application to send emails, this is required, or users won't be able to verify!
