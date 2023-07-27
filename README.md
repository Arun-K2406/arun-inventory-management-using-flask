# arun-inventory-management-using-flask
# Inventory-Manager
An inventory management system using Flask

## Getting Started


## Clone this repository and set your path to it's folder, to get it up and running on your local system.

```
git clone https://github.com/marination/Inventory-Manager.git
cd Inventory-Manager
```
## What to look for here?
- [System Summary](#system-summary)
- [Running the app](#running-the-app)
- Features
  1. [Adding Products and Locations](#adding-products-and-locations)
  2. [Deleting Products and Locations](#deleting-products-and-locations)
  3. [Moving Products](#moving-products)
  4. [Editing Products and Locations](#editing-products-and-locations)
- [Built Using](#built-using)
- [License](#license)
### Prerequisites

To run this system you will need :

- Python 3
- Flask
- 
Assuming you have Python, proceed to install the rest using the command below:

```
pip3 install -r requirements.txt
```
## System Summary

This system is built to simulate a warehouse environment and handles balancing quantities over warehouses. It has 4 main views including *Overview*,*Products*,*Locations* and *Transfers*. **Products** and **Locations** let you add,edit and delete entries from the system. **Transfers** lets you move items into the central warehouse, out of the central warehouse; also to and from various locations.It also displays transfer history. **Overview** will display products,warehouses and their respective balanced quantities.


## Running the app
1) Set your current path to where the cloned folder is and run the file **run.py**

2) Either copy paste the url as shown above into your browser **or** simply check into *localhost:5000/* as shown below. You will see the initial views of each page as no actions are performed.

## Features

### Adding Products and Locations
Products require product name and quantity to be filled. Location only requires location name

### Deleting Products and Locations
Deleting only requires a button click, although the transfers(if any) will remain in the history.

### Moving products
Here products can be moved to a location, from a location as well as to and from a location. Products need to initially be added to various locations from the central warehouse.

### Editing Products and Locations
Change in product or loaction name creates changes in their names in the history and system overview.So, you can rectify a spelling error and still not loose any data.

# Built using
- Flask

# License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

