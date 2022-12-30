# adidas Store Theme

This SPA is created based on the VTEX IO Store Framework.

Through the use of vtex native components adidas Store Theme allow users to access e-commerce features like:

* Navigation menu
* Login
* Minicart
* Product detail page
  * Reviews and ratings
  * review form
* Product list page
  * products based on: department, category or subcategory
  * filters and orders

and custom components: 

* Whatsapp contact button

## Preview
#### 1 - Home Page 
#### 2 - Mega menu 
#### 3 - Tab-layout - slider-layout
#### 4 - Footer

[![home-preview.jpg](https://i.postimg.cc/rsYqYNDk/home-preview.jpg)](https://postimg.cc/wRLK1J5f)

## Configuration

### Step 1 -  Basic setup

Access the VTEX IO [basic setup guide](https://vtex.io/docs/getting-started/build-stores-with-store-framework/1) and follow all the given steps. 

By the end of the setup, you should have the VTEX command line interface (Toolbelt) installed along with a developer workspace you can work in.

### Step 2 - Cloning adidas Store Theme

[Clone](https://github.com/JSebastian101/adidas-vtex) this repository to your local files to be able to effectively start working on it.

Then, access the repository's directory using your terminal. 

### Step 3 -  Installing required apps

In order to use Adidas Store Theme your account has to be linked to `itgloberspartnercl`. 

Run  `vtex list`  and check whether dependencies are missing on your enviroment. If needed, run `vtex install vtex.**dependency-name**` 

### Step 4 -  Uninstalling any existing theme

By running `vtex list`,  you can verify if any theme is installed.

It is common to already have a `vtex.store-theme`  installed when you start the store's front development process. 

Therefore, if you find it in the app's list, copy its name and use it together with the command `vtex uninstall`. For example:

```json
vtex uninstall vtex.store-theme
```

### Step 5 - Run and preview your store

Then time has come to upload all the changes you made in your local files to the platform. For that, use the `vtex link` command. 

If the process runs without any errors, the following message will be displayed: `App linked successfully`. Then, run the `vtex browse` command to open a browser window having your linked store in it.

This will enable you to see the applied changes in real time, through the account and workspace in which you are working.

## peerDependencies
peerDependencies used in adidas Store Theme:

- "vtex.wish-list": "1.x",
- "vtex.questions-and-answers": "0.x"

## Dependencies
These are the Dependencies used in the store theme:

- "vtex.store": "2.x",
- "vtex.store-header": "2.x",
- "vtex.product-summary": "2.x",
- "vtex.store-footer": "2.x",
- "vtex.store-components": "3.x",
- "vtex.styleguide": "9.x",
- "vtex.slider": "0.x",
- "vtex.carousel": "2.x",
- "vtex.shelf": "1.x",
- "vtex.menu": "2.x",
- "vtex.minicart": "2.x",
- "vtex.product-details": "1.x",
- "vtex.product-kit": "1.x",
- "vtex.search": "2.x",
- "vtex.search-result": "3.x",
- "vtex.login": "2.x",
- "vtex.my-account": "1.x",
- "vtex.flex-layout": "0.x",
- "vtex.rich-text": "0.x",
- "vtex.store-drawer": "0.x",
- "vtex.locale-switcher": "0.x",
- "vtex.product-quantity": "1.x",
- "vtex.product-identifier": "0.x",
- "vtex.product-specification-badges": "0.x",
- "vtex.product-specifications": "1.x",
- "vtex.product-review-interfaces": "1.x",
- "vtex.telemarketing": "2.x",
- "vtex.order-placed": "2.x",
- "vtex.stack-layout": "0.x",
- "vtex.tab-layout": "0.x",
- "vtex.responsive-layout": "0.x",
- "vtex.slider-layout": "0.x",
- "vtex.iframe": "0.x",
- "vtex.breadcrumb": "1.x",
- "vtex.sticky-layout": "0.x",
- "vtex.add-to-cart-button": "0.x",
- "vtex.store-icons": "0.x",
- "vtex.modal-layout": "0.x",
- "vtex.product-list": "0.x",
- "vtex.disclosure-layout": "1.x",
- "vtex.store-link": "0.x",
- "vtex.condition-layout": "2.x",
- "vtex.checkout-summary": "0.x",

## Custom Apps
These are the custom apps that I have created for the theme store, I will leave the links to the repositories so they can be used:
- ["itglobers.itglobers-whatsapp-button": "0.x"](https://github.com/JSebastian101/itglobers-whatsapp-button)
- ["itgloberspartnercl.bullets-diagramation": "0.x"](https://github.com/JSebastian101/bullets-diagramation),
- ["itglobers.add-to-cart-info": "0.x"](https://github.com/JSebastian101/itglobers-add-to-cart-info),
- ["itglobers.custom-department-search": "0.x"](https://github.com/JSebastian101/department-search),
- ["itglobers.pdf-reader": "0.x"](https://github.com/JSebastian101/pdf-reader),
- ["itglobers.quick-order": "0.x"](https://github.com/JSebastian101/quick-order),
- ["itglobers.special-diagramation": "0.x"](https://github.com/JSebastian101/diagramation-template)
