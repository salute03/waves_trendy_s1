# Waves Trendy

We at [__Waves Trendy__](https://salute03-waves-trendy.herokuapp.com/) are dedicated to provide beautiful and new trend fashion dresses, uniting and sustainable products to individuals, love birds and families. With our method to only produce whats demanded by our customers and delivering longlasting, high quality products we want to counter the biggest problems of the western society. Our products are locally produced in America and we only use materials where we know the origin, to guarantee 100% ethical and sustainable products.

This site is the final Milestone Projects that made up the Full Stack Web Development Course at Code Institute. The core requirements focus on bulding a fullstack site with the use of Django, Python, JavaScript, HTML, CSS and a relational database. The final result is hosted on Heroku, while storing static and media files on an S3 Cloudstorage from AWS. The store is connected to [Stripe](www.stripe.com).

To test the site incl. the checkout process please use the test credit card number provided in the [Stripe Documentation](https://stripe.com/docs/testing):

+ __Number__: 4242 4242 4242 4242
+ __Exp. Date__: Anything (e.g. 02/24)
+ __CVC__: Anything (e.g. 242)

# Table of Content

- [Waves Trendy](#waves-trendy)
- [Table of Content](#table-of-content)
- [UXD Considerations](#uxd-considerations)
  * [Purpose and Aim of the Project](#purpose-and-aim-of-the-project)
  * [Design process](#design-process)
  * [Target group](#target-group)
  * [Epics & User Stories](#epics---user-stories)
  * [Layout, Styling & Wireframes](#layout--styling---wireframes)
- [Information Architecture](#information-architecture)
  * [Application Framework](#application-framework)
  * [Database Selection](#database-selection)
  * [Data Models](#data-models)
- [Features](#features)
  * [Navbar](#navbar)
  * [Landing Page](#landing-page)
  * [Shop](#shop)
  * [Highlights](#highlights)
  * [Cart](#cart)
  * [Checkout](#checkout)
  * [Sign Up & login:](#sign-up---login-)
  * [Registered Users: Useraccount](#registered-users--useraccount)
  * [Registered Users: Wishlist](#registered-users--wishlist)
  * [Store Management:](#store-management-)
- [Technologies Applied](#technologies-applied)
  * [Databases](#databases)
  * [Languages](#languages)
  * [Frameworks](#frameworks)
  * [Libraries, Tools](#libraries--tools)
  * [Hosting](#hosting)
- [Testing](#testing)
- [Deployment](#deployment)
  * [Prerequisites to work with this Site](#prerequisites-to-work-with-this-site)
  * [Local Deployment: Step-by-Step Instructions](#local-deployment--step-by-step-instructions)
  * [Deployment to Heroku: Step-by-Step Instructions](#deployment-to-heroku--step-by-step-instructions)
- [References, Credits & Acknowledgment](#references--credits---acknowledgment)
  * [Credits](#credits)
  * [Content & Products](#content---products)
  * [Media](#media)
  * [Acknowledgements](#acknowledgements)
  * [References](#references)
- [Fair use disclaimer](#fair-use-disclaimer)

# UXD Considerations

## Purpose and Aim of the Project

The aim of this project is to create an ecommerce shop for sustainable clothing and some home equitment. 
The goal is to create this shop as an interactive fullstack website that allows customers to browse products, 
make purchases by credit card and if registered manage a wishlist or see their orderhistory. 
These goals should be supported by providing a clean and easy to use website that allows seamless navigation and has a low bounce rate.

## Design process
Before laying out the project and creating an initial design market research was done. 
During this research phase the following questions were also acknowledged: 
* How do other stores look?
* What are typical design patterns used across stores?
* Which site are appealing to me?
* Which kind of stores fit to my business idea? 


## Target group

The shop is targeted to women and men alike.
 The typical age of a shopper is estimated to be between 25 and 40 years. Especially couples and small families are targeted with the products. 
All customers have mindset respecting the environment and favoring sustainable products. 
 The income of the target group is an average mid to high household income. Furthermore the target group has a passion for living outdoors and owning sustainable high quality products to use in day to day life.

## Epics & User Stories
Before the start of the Project the Epics and User Stories were defined and written out to have complete set of necessary features to get the site going. In total 6 Epics were defined and user stories were broken down into 3 user groups:
* regular __site visitors__
* __registered users__
* the __store manager/owner__.

### EPIC: Browse Site
As a __site visitor__, i want to...
* ... __access the website__ with any device (smartphone, tablet, desktop), so that i am able to visit the shop anytime and anywhere.
* ... have __easy navigation__, to quickly solve the reason for my visit.
* ... have __information about the brand__, to get to know the company and understand their mission and story.
* ... be able to __contact the company__, so that i quickly can get in touch if i have a question or issue.

### Epic: Browse Products
As a __site visitor__, i want to...
* ... browse products by __category and productline__, so that i quickly find what i am looking for.
* ... __sort products__, to adjust the order according to my needs.
* ... be able to __search for specific products__, to quickly get what i need.
* ... to __access product details__, to get more information on an item.
* ... be able to __choose a size__, to order the necessary items according to my needs.

### Epic: Manage Cart & Make Purchase
As a __site visitor__, i want to...
* ... see all my __items in a cart__, so that i have an overview of my potential purchase.
* ... be able to __reduce / increase quantity__, so that i can order my prefered amount.
* ... be able to __remove an item from my cart__, so that i can manage my cart efficiently.
* ... be able to __checkout from the cart__ view, so that i can quickly finish my purchase.
* ... be able to __pay a order by credit card__, so that i don't have to deal with an invoice and money transfer.
* ... __receive an order confirmation__, so that i know my order was received.

As a __registered user__, i want to...
* ... have my __details prefilled from my profile__, so that i quickly can finish my purchase

### Epic: Registration & Useraccount

As a __site visitor__, i want to...
* ... be able to __sign up to the store__, so that i can track orders and have my data prefilled in the order form.

As a __registered user__, i want to...
* ... be __able to login__, so that i can access my useraccount.
* ... be able to __see my order history__, so that i know what i've purchased in the past.
* ... __manage my personal details__, so that i can quickly update my data if something changes.

### Epic: Manage Wishlist
As a __registered user__, i want to...
* ... __add/remove items to my wishlist__, so that can save items for later purchase to my useraccount.
* ... have an __overview of my wishlist__, to get an overview of my already added products.

### Epic: Store Management
As a __store owner__, i want to...
* ... be able to __manage the products, categories, productlines and productvariants__, so that i have an overview of my inventory.
* ... __manage blog entries__, to add new/edit posts on the blog to provide customers some additional value.
* ... __manage FAQs__, so that i can quickly update often asked questions

## Layout, Styling & Wireframes

The wireframes were created in Figma. Figma is a cloud based desing tool which allows you to rapidly create prototypes, wireframes and layouts [Figma](www.figma.com)


#### Wireframes

The whole figma project can be accessed here:
[Waves Trendy](https://www.figma.com/file/Z94iHA4VJTeJ4RQkgj0uXB/Untitled?node-id=0%3A1)


# Information Architecture 

## Application Framework
The project brief required to base the project on the [Django](https://www.djangoproject.com/) application framework - "The web framework for perfectionists with deadlines". Django is an open source python web framework that takes away the burdens of regular web development and allows developers to quickly build a secure, scalable and state-of-the art app.

## Database Selection

During development the built-in SQLite3 database from django is used. However, for the deployment to Heroku a switch to postgressql was undertaken.
[Django’s authentication system](https://docs.djangoproject.com/en/3.1/ref/contrib/auth/) in combination with [django-allauth](https://django-allauth.readthedocs.io/en/latest/overview.html) is used to manage users and permissions.
The structure of the products and checkout app are based on the [Boutique Ado](https://github.com/ckz8780/boutique_ado_v1) project from Code Institute and customized to the specific project needs.
## Data Models

### Categories

| Name         | Type       | Example Data                                                 |
|--------------|------------|--------------------------------------------------------------|
| name         | CharField(max_length=254)  | grown_ups                                                    |
| display_text | CharField(max_length=254)  | Grown Ups                                                    |
| image        | ImageField(null=True, blank=True)                                           |
| image_url    | URLField(max_length=1024, null=True, blank=True)  |

### Productline

| Name         | Type      | Example Data |
|--------------|-----------|--------------|
| name         | CharField(max_length=50) | tshirt       |
| display_text | CharField(max_length=254) | T-Shirt      |

### Products
| Name                | Type                                                                                           | Example Data    |
|---------------------|------------------------------------------------------------------------------------------------|-----------------|
| category            | ForeignKey( 'Category')                                                                        | 1               |
| productline         | ForeignKey( 'ProductLine')                                                                     | 1               |
| name                | CharField( max_length = 254 )                                                                  | passionate      |
| display_text        | CharField( max_length = 254 )                                                                  | Passionate Puffin |
| price               | DecimalField(max_digits=6, decimal_places=2, validators=[MinValueValidator(0.01)], blank=True) | 49.95     |
| discount_price      | DecimalField(max_digits=6, decimal_places=2, validators=[MinValueValidator(0.01)], blank=True) | 39,96     |
| is_on_sale          | BooleanField(default=False)                                                                    | True      |
| avail_for_pre_order | BooleanField( default = False )                                                                | False     |
| date_of_dispatch    | CharField( max_length = 254 ,  blank = True ,  null = True )                                   | null      |
| discontinued        | BooleanField( default = False )                                                                | false     |
| image               | ImageField( null = True ,  blank = True )                                                      | passionatepuffin.png |
| image_url           | URLField( max_length = 1024 ,  null = True ,  blank = True )                                   |  |
| description         | TextField( null = True ,  blank = True )                                                       |  |
| is_featured         | BooleanField( default = False ,  null = True ,  blank = True )                                 | True        |
| color               | CharField( max_length = 254 ,  null = True )                                                   |         |
| material_1          | CharField( max_length = 254 ,  null = True ,  blank = True )                                   |      |
| material_2          | CharField( max_length = 254 ,  null = True ,  blank = True )                                   | ""          |

### Productsize

| Name         | Type                                                | Example                                                                                                          |
|--------------|-----------------------------------------------------|------------------------------------------------------------------------------------------------------------------|
| SIZE_CHOICES |                                                     | [('NO', 'None'), ('XS', 'Extra Small'), ('S', 'Small'), ('M', 'Medium'), ('L', 'Large'), ('XL', 'Extra Large'),] |
| shirt_size   | CharField( max_length = 2 ,  choices =SIZE_CHOICES) | XS                                                                                                               |

### Productvariant

| Name     | Type                                                  | Example |
|----------|-------------------------------------------------------|---------|
| product  | ForeignKey('Product', on_delete=models.CASCADE)       | null      |
| size     | ForeignKey('ProductSize', on_delete=models.CASCADE)   | XS      |
| quantity | IntegerField( validators =[MinValueValidator( 0.0 )]) | 9       |

### Order

| Name              | Type           |
|-------------------|----------------|
| order_number      | CharField( max_length = 32 ,  null = False ,  editable = False )    |
| user_profile      | ForeignKey(UserAccount,  on_delete =models.SET_NULL,null = True ,  blank = True ,related_name = 'orders' ) |
| order_status      | CharField( max_length = 1 ,  choices =STATUS_OPTIONS,                                      default = '0' )  |
| first_name        | CharField( max_length = 50 ,  null = False ,  blank = False )                                                |
| last_name         | CharField( max_length = 50 ,  null = False ,  blank = False )                                                |
| email             | EmailField( max_length = 254 ,  null = False ,  blank = False )                                              |
| phone_number      | CharField( max_length = 20 ,  blank = True )                                                                 |
| country           | CountryField( blank_label = 'Country' ,  null = False ,  blank = False )                                     |
| zipcode           | CharField( max_length = 20 ,  null = True ,  blank = False )                                                 |
| town_or_city      | CharField( max_length = 40 ,  null = False ,  blank = False )                                                |
| street_address1   | CharField( max_length = 80 ,  null = False ,  blank = False )                                                |
| street_address2   | CharField( max_length = 80 ,  blank = True )                                                                 |
| total_order       | DecimalField( max_digits = 10 ,  decimal_places = 2 ,  null = False ,  default = 0 )                         |
| total_tax         | DecimalField( max_digits = 10 ,  decimal_places = 2 ,  null = False ,  default = 0 )                         |
| tax_rate          | DecimalField( max_digits = 6 ,  decimal_places = 2 ,  null = False ,  default = 0 )                          |
| delivery_cost     | DecimalField( max_digits = 10 ,  decimal_places = 2 ,  null = False ,  default = 0 )                         |
| grand_total       | DecimalField( max_digits = 10 ,  decimal_places = 2 ,  null = False ,  default = 0 )                         |
| date_order_placed | DateTimeField( auto_now_add = True )                                                                         |
| original_cart     | TextField( null = False ,  blank = False ,  default = '' )                                                   |
| stripe_pid        | CharField( max_length = 254 ,  null = False ,  blank = False ,  default = '' )                               |

### OrderLineItem

| Name           | Type                                                                                                         |
|----------------|--------------------------------------------------------------------------------------------------------------|
| order          | ForeignKey(Order,  null = False ,  blank = False ,  on_delete =models.CASCADE,  related_name = "lineitems" ) |
| productvariant | ForeignKey(ProductVariant,  null = False ,  blank = False ,  on_delete =models.CASCADE)                      |
| quantity       | IntegerField( blank = False ,  default = 0 )                                                                 |
| lineitem_total | DecimalField( max_digits = 6 ,  decimal_places = 2 ,  null = False ,  default = 0 ,  editable = False )      |

### Useraccount

| Name                    | Type                                                                   |
|-------------------------|------------------------------------------------------------------------|
| user                    | OneToOneField(User,  on_delete =models.CASCADE)                        |
| default_phone_number    | CharField( max_length = 20 ,  null = True ,  blank = True )            |
| default_street_address1 | CharField( max_length = 80 ,  null = True ,  blank = True )            |
| default_street_address2 | CharField( max_length = 80 ,  null = True ,  blank = True )            |
| default_zipcode         | CharField( max_length = 20 ,  null = True ,  blank = True )            |
| default_town_or_city    | CharField( max_length = 40 ,  null = True ,  blank = True )            |
| default_country         | CountryField( blank_label = 'Country' ,  null = True ,  blank = True ) |

### Wishlist

| Name            | Type                                                                                    |
|-----------------|-----------------------------------------------------------------------------------------|
| user_profile    | OneToOneField(UserAccount,  on_delete =models.CASCADE, null = False ,  blank = False)   |
| wished_products | ManyToManyField(Product, related_name = 'userwishlists' )                               |

### FAQs

| Name             | Type                                                                                                              |
|------------------|-------------------------------------------------------------------------------------------------------------------|
| CATEGORY_CHOICES | [( '1' ,  'General' ), ( '2' ,  'Return' ), ( '3' ,  'Pre Order' ), ( '4' ,  'Delivery' ), ( '5' ,  'Payment' ),] |
| category         | CharField( max_length = 1 ,  choices =CATEGORY_CHOICES)                                                           |
| name             | CharField(max_length = 120 , null = True, blank = False )                                                         |
| title            | CharField(max_length = 120 ,  null = True ,  blank = False )                                                      |
| answer           | TextField()                                                                                                       |
| created_at       | DateTimeField(auto_now_add = True ,null = False )                                                                 |
| updated_at       | DateTimeField(auto_now = True ,  null = False)                                                                    |
### Blog 

| Name                | Type                                                                                |
|---------------------|-------------------------------------------------------------------------------------|
| author              | ForeignKey(UserAccount,  on_delete =models.CASCADE,  null = False ,  blank = True ) |
| title               | CharField(max_length=120, null=True, blank=False)                                   |
| subtitle            | CharField(max_length=180, null=True, blank=False)                                   |
| body                | TextField()                                                                         |
| slug                | SlugField(unique=True, max_length=250, default=None)                                |
| created_at          | DateTimeField(auto_now_add=True, null=False)                                        |
| updated_at          | DateTimeField(auto_now=True, null=False)                                            |                                                                      |                 |

# Features
The following features were thought of. 
:white_check_mark: - Mark Features that made it into the deployed Project
:toolbox: - Mark Features that are interessting for Future Development

## Navbar
* Logged in and non-logged in users see different options :white_check_mark:
* Searchbar opens below nav when search icon is clicked :white_check_mark:
* Fixed to top and transparent :white_check_mark:



## Landing Page
* Caroussel with image also behind nav :white_check_mark:
* Random featured products are chosen to be displayed in caroussel :white_check_mark:
* Images for featured icons are different from the product picture to be even more appealing :toolbox:


## Shop
* Products can be browsed by Category
* Products can be browsed by Category & Productline (e.g.T-Shirt) 
* Products can be sorted by...  
   ...Featured Products
   ...Price 
   ...Color  
   ...Name  
* Products have different labels based on  
   Normal Product  
   Sale Product 
   Pre-Order Productn
* Product Details have a Select Option if different sizes are available.
* Product Details have only a "Add to Bag" button if unisize item.
* Partnerlook Section sorts products by name to display matching items side by side.
* Product can be shared on social media :toolbox:

If registered: 
* Product Details allow user to add/remove product to/from wishlist.

## Highlights
* Products a prominently display 
* only featured items are rendered

## Bag
* Bag is present in Side Drawer Container 
* Newest Item is always presented on top 
* Total inkl. Tax & Shipping
* Checkout straight from Cart Side Drawer 
* Add to cart renders updated cart via Ajax-Request
* Increase/Decrease Quantity request via Ajax within Side Drawer Bag :toolbox:
* Remove Items from Cart ia Ajax-Request within Side Drawer Bag :toolbox:
* Reserve requested item & quantity to for 10 Min. to avoid checkouts with unavailable products :toolbox:

If registered: 
* attach cart to userprofile instead of saving to session :toolbox:

## Checkout
* Order summary :white_check_mark:
* Form to enter shipping address :white_check_mark:
* Payment via Credit Card :white_check_mark:
* Users gets order confirmation by mail :white_check_mark:
* general discount codes can be used :toolbox:
* personalized discount codes can be used :toolbox:
* Users receives order updates when order status changes :toolbox:

If registered: 
* Form is prefilled with available user data :white_check_mark:
* Form data can be saved to userprofile :white_check_mark:

## Sign Up & login:
* Sign up can be undertaken :white_check_mark:
* Sign up also collected first and last name :white_check_mark:
* login can be undertaken :white_check_mark:
* Password reset :white_check_mark:
* Delete account :toolbox:
+ Sign in with apple or google account :toolbox:

## Registered Users: Useraccount
* User can look up saved address information :white_check_mark:
* User can update address information :white_check_mark:
* User can see past orderes :white_check_mark:
* User can enter detail view of past orders :white_check_mark:

## Registered Users: Wishlist
* User can add/remove items to personal wishlist from product details :white_check_mark:
* User can view stored wishlist items :white_check_mark:
* Users can add items to wishlist from product overview :toolbox:
* users can add items and size to wishlist :toolbox:
* users can immediatley transform wishlist into order :toolbox:

## Store Management:
* ... can create/read/update/delete products in Django-Admin-View
* ... can create/read/update/delete blogposts in Django-Admin-View
* ... can create/read/update/delete FAQs in Django-Admin-View
* ... can create/read/update/delete Users in Django-Admin-View
* ... Order Management system :toolbox:


# Technologies Applied
The following technologie were used during the development of the project.

## Databases
- Sqlite3 (https://www.sqlite.org/index.html)
- postgresSQL (https://www.postgresql.org/)
## Languages
- CSS (https://www.w3.org/Style/CSS/)
- HTML (https://html.spec.whatwg.org/multipage/)
- Javascript (https://developer.mozilla.org/en-
US/docs/Web/JavaScript)
- Python (https://www.python.org/)
## Frameworks
- Bootstrap (https://www.bootstrapcdn.com/)
- Django (https://www.djangoproject.com/)
- jQuery (https://jquery.com/)
## Libraries, Tools 
- Google Fonts (https://fonts.google.com/)
- Gitpod (https://www.gitpod.io/)
- Figma (https://www.figma.com/)
- Boto3 (https://boto3.amazonaws.com/v1/documentation/api/latest/index.html)
- Coverage (https://coverage.readthedocs.io/en/v4.5.x/)
- Dj-Database-URL (https://pypi.org/project/dj-database-url/)
- Django-Countries (https://pypi.org/project/django-countries/)
- Django-Heroku (https://pypi.org/project/django-heroku/)
- Django-Storages (https://django-storages.readthedocs.io/en/latest/)
- Git (https://git-scm.com/)
- GitHub (https://github.com/)
- Gunicorn (https://pypi.org/project/gunicorn/)
- Jigsaw – CSS Validation (https://jigsaw.w3.org/css-validator/)
- JS Hint (https://jshint.com/)
- PEP8 (http://pep8online.com/)
- Pillow (https://pillow.readthedocs.io/en/stable/)
- PIP (https://pip.pypa.io/en/stable/installing/)
- Psycopg2 (https://pypi.org/project/psycopg2/)
- Stripe (https://stripe.com/gb)
- W3C – HTML Validation (https://validator.w3.org/)
- MarkdownTOC (http://ecotrust-canada.github.io/markdown-toc/')
## Hosting
- Heroku (https://www.heroku.com/)
- AWS S3 Bucket (https://aws.amazon.com/)


# Testing

A detailed description about the testing process and results can be found in the TESTING.md To give a brief overlook of the feature testing this table gives a codensed overview of the tested, features, devices, browsers and results:

| Test Case                     |    iPhone Safari   |    iPhone Chrome   |     iPhone Edge    |     iPad Safari    |      iPad Edge     |     iPad Brave     | Mac  Edge          | Mac Safari         | Mac Chrome         |
|-------------------------------|:------------------:|:------------------:|:------------------:|:------------------:|:------------------:|:------------------:|--------------------|--------------------|--------------------|
| Test Navbar                   | :white_check_mark: | :white_check_mark: | :white_check_mark: | :white_check_mark: | :white_check_mark: | :white_check_mark: | :white_check_mark: | :white_check_mark: | :white_check_mark: |
| Landing Page                  | :white_check_mark: | :white_check_mark: | :white_check_mark: | :white_check_mark: | :white_check_mark: | :white_check_mark: | :white_check_mark: | :white_check_mark: | :white_check_mark: |
| Shop                          | :white_check_mark: | :white_check_mark: | :white_check_mark: | :white_check_mark: | :white_check_mark: | :white_check_mark: | :white_check_mark: | :white_check_mark: | :white_check_mark: |
| Highlights                    | :white_check_mark: | :white_check_mark: | :white_check_mark: | :white_check_mark: | :white_check_mark: | :white_check_mark: | :white_check_mark: | :white_check_mark: | :white_check_mark: |
| Cart                          | :white_check_mark: | :white_check_mark: | :white_check_mark: | :white_check_mark: | :white_check_mark: | :white_check_mark: | :white_check_mark: | :white_check_mark: | :white_check_mark: |
| Checkout                      | :white_check_mark: | :white_check_mark: | :white_check_mark: | :white_check_mark: | :white_check_mark: | :white_check_mark: | :white_check_mark: | :white_check_mark: | :white_check_mark: |
| Sign Up                       | :white_check_mark: | :white_check_mark: | :white_check_mark: | :white_check_mark: | :white_check_mark: | :white_check_mark: | :white_check_mark: | :white_check_mark: | :white_check_mark: |
| Registered Users: Useraccount | :white_check_mark: | :white_check_mark: | :white_check_mark: | :white_check_mark: | :white_check_mark: | :white_check_mark: | :white_check_mark: | :white_check_mark: | :white_check_mark: |
| Registered Users: Wishlist    | :white_check_mark: | :white_check_mark: | :white_check_mark: | :white_check_mark: | :white_check_mark: | :white_check_mark: | :white_check_mark: | :white_check_mark: | :white_check_mark: |
# Deployment

This site is deployed to heroku and the versioning was done with gitpod and the Repository is hosted on Github.


## Prerequisites to work with this Site

This project can be used for development with the following tools:

- IDE of Choie (i prefer Gitpod)
- Python3, PIP & Git should be installed

Furthermore accounts with the following services are used in this project:

- Stripe
- AWS S3 Storage
- Gmail

## Local Deployment: Step-by-Step Instructions

Official Github Documentation on cloning a repositiory: [Github - Cloning Repos]

1. Navigate to Mainpage of the repository
2. Click on "Code" button
3. Choose "Clone with HTTPs" & copy URL
4. Open Terminal
5. Change the current working directory to prefered location
6. Type git clone and past copied URL ```git clone https://github.com/salute03/waves_trendy_s1```
7. Press Enter to create local Clone - Make sure your environment supports python3 -
8. Type ```pip3 install -r requirements.txt``` into Terminal
9. Setup the environment variables. This process is differnet depending on the used IDE. Gitpod supports global Environments for the development process. Therefore they were stored in the settings. The following variables are needed:
    ```
    DEVELOPMENT=True   
    STRIPE_PUBLIC_KEY = <YOUR STRIPE_PUBLIC_KEY>
    STRIPE_SECRET_KEY = <YOUR STRIPE_SECRET_KEY>
    STRIPE_WH_SECRET = <YOUR STRIPE_WH_SECRET>
    ```
10. Migrate the models and create the database by typing the following commands into the terminal:
    1. ```python3 manage.py makemigrations```  
    2. ```python3 manage.py migrate```
11. Import the provided fixtures in the following order (copy&paste if you like): 
    1. ```python3 manage.py loaddata categories```
    2. ```python3 manage.py loaddata productline```
    3. ```python3 manage.py loaddata products```
    4. ```python3 manage.py loaddata proudctsize```
    5. ```python3 manage.py loaddata productvariants```
    6. ```python3 manage.py loaddata blog ```
    7. ```python3 manage.py loaddata faq ```
12. Create a superuser for accessing the django admin view with the following command:
    ```python3 manage.py createsuperuser``` You will be asked for an email address, username and password.
13. You should be all set and when using the command ```python3 manage.py runserver``` the project should run.
14. You can access the django admin view by adding ```~/admin``` to the end of your (local) URL.

## Deployment to Heroku: Step-by-Step Instructions

This project is deployed to Heroku. For the deployment the following steps were/are necessary:

1. Create/Log in to your Heroku account and create a new App.
2. Install Heroku Add-on Heroku Postgres from the Resources tab. The free ```Hobby Dev``` version is fine. Now click the Provision button to add it to your project.
3. Create requirements.txt from your project with the help of ```pip3 freeze > requirements.txt``` (already provided within the repository)
4. Create a Procfile ```echo web: gunicorn puffins.wsgi:application > Procfile``` (already provided within the repository)
5. Commit changes to Git ```git add .``` followed by ```git commit -m "Deploy: Updated Procfile"``` (already provided within the repository)
6. Set the environment variables in Heroku Settings > Reveal Config Variables
    The following Variables must be set:
    ```
    USE_AWS = TRUE
    AWS_ACCESS_KEY_ID = <YOUR AWS_ACCESS_KEY_ID>
    AWS_SECRET_ACCESS_KEY = <YOUR AWS_SECRET_ACCESS_KEY>
    DATABASE_URL = <YOUR DATABASE_URL> (Set by Heroku Postgres)
    EMAIL_HOST_USER = <YOUR EMAIL_HOST_USER>
    EMAIL_HOST_PASSWORD = <YOUR EMAIL_HOST_PASSWORD>
    DEFAULT_FROM_EMAIL = <YOUR DEFAULT_FROM_EMAIL>
    STRIPE_PUBLIC_KEY = <YOUR STRIPE_PUBLIC_KEY>
    STRIPE_SECRET_KEY = <YOUR STRIPE_SECRET_KEY>
    STRIPE_WH_SECRET = <YOUR STRIPE_WH_SECRET>
    ```
7. Extract the DATABASE_URL Value from the Heroku Settings and set it up in your IDE or local .env file. Make sure to keep this DATABASE_URL a secret and definitly don't commit it to Github.
8. To test if the Postgres database is connected to your IDE you can make use of the command ```python3 manage.py showmigrations```. This should show undone migrations for all models.
9. Now migrate the models and create the postgres database on heroku by typing the following commands into the terminal:
    1. ```python3 manage.py makemigrations```  
    2. ```python3 manage.py migrate```
10. To setup the data in the database import the provided fixtures in the following order (copy&paste if you like): 
    1. ```python3 manage.py loaddata categories```
    2. ```python3 manage.py loaddata productline```
    3. ```python3 manage.py loaddata products```
    4. ```python3 manage.py loaddata proudctsize```
    5. ```python3 manage.py loaddata productvariants```
11. Create a superuser for the Postgres database for accessing the django admin view with the following command:
    ```python3 manage.py createsuperuser``` You will be asked for an email address, username and password.
12. Log in to heroku from your terminal ```heroku login -i```
13. Add exisitng repository to Heroku heroku ```git:remote -a <your repository>```
14. Push changes to Heroku ```git push heroku main```
15. Visit the app url from heroku and check out your great site!

# References, Credits & Acknowledgment

## Credits
Code Institute


## Media

Category Images: 
* [Code Institute](www.codeinstitute.net) Boutique Ado-Poject]

## Acknowledgements

Special Thanks to...
* ... my Code-Institute Mentor
* ... Tutors and Fellow Students of slack

## References 
* The codes in this project are from  the [Code Institute](www.codeinstitute.net) Boutique Ado-Poject lessons and was extended and modified to personal needs. 



# Fair use disclaimer

This is for educational use