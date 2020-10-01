# Item Catalog -  head line i like it

> Metin Muglu

## Aboutyour

this project  is my 2 projects for Udacity Full Stack Nanodegree. It is a product catalog project. Contains the main title and subtypes of the product. You can login via Facebook. When login is made, authorizations are obtained.

'This program uses third party authorization with Google or Facebook. Some of the technologies used in this app are Flask, Bootsrap and SQLite'.


## Skills used for this project##
- Python
- Jinja2
- SQLAchemy
- OAuth
- Facebook / Google Login
- HTML
- CSS
- Bootstrap
- Flask


## Some things you might need
- [Udacity Vagrantfile](https://github.com/udacity/fullstack-nanodegree-vm)
- [VirtualBox](https://www.virtualbox.org/wiki/Downloads)
- [Vagrant](https://www.vagrantup.com/)

## Getting Started

- Install Vagrant and VirtualBox
- Clone the Vagrantfile from the Udacity Repo
- Clone this repo into the `catalog/` directory found in the Vagrant directory
- Run `vagrant up` to run the virtual machine, then `vagrant ssh` to login to the VM
- from the main directory run `sudo pip install -r requirements`
- run application with `python application.py` from within its directory
- go to `http://localhost/categories` to access the application


## JSON Endpoints##

`/api/v1/catalog.json` - Returns JSON of all items in catalog

<img src="assets/catalogJSON.png" width="800">

`/api/v1/categories/<int:category_id>/item/<int:catalog_item_id>/JSON` - Returns JSON of selected item in catalog

<img src="assets/catalog-itemJSON.png" width="800">

`/api/v1/categories/JSON` - Returns JSON of all categories in catalog

<img src="assets/categoriesJSON.png" width="800">

#### --------------------------------------
#### CRUD for category items
#### --------------------------------------

`/categories/<int:category_id>/` or `/categories/<int:category_id>/items/` - returns items in category

<img src="assets/catalog-item.png" width="800">

`/categories/<int:category_id>/item/<int:catalog_item_id>/` - returns category item

<img src="assets/catalog-item-detail.png" width="800">

`/categories/item/new` - return "This page will be for making a new catalog item

<img src="assets/catalog-item-new.png" width="800">

`/categories/<int:category_id>/item/<int:catalog_item_id>/edit` - return "This page will be for making a updating catalog item"

<img src="assets/catalog-item-edit.png" width="800">

`/categories/<int:category_id>/item/<int:catalog_item_id>/delete` - return "This page will be for deleting a catalog item"

<img src="assets/catalog-item-delete.png" width="800

## REST Endpoints

#### --------------------------------------
#### CRUD for categories
#### --------------------------------------

`/` or `/categories` - Returns catalog page with all categories and recently added items

<img src="assets/categories1.png" width="800">

<img src="assets/categories-loggedin.png" width="800">

`/categories/new` - Allows user to create new category

<img src="assets/category-new.png" width="800">

`/categories/<int:category_id>/edit/` - Allows user to edit an existing category

<img src="assets/category-edit.png" width="800">

`/categories/<int:category_id>/delete/` - Allows user to delete an existing category

<img src="assets/category-delete.png" width="800">

