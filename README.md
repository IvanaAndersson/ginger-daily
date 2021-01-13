## Header and navigation
* Liquid files used: 
    * **header-layout-01.liquid** is for the desktop menu, 
    * **header.liquid** uses the mobile menu (under 1024px)
    * **site-nav.liquid** is for the megamenu
    * **cart-related-products** for the related products in the cart drawer
    * **cart-item-new** for the separate products in the cart drawer (cart-left)
* SCSS files used: header-and-footer.scss

## Popups and cart drawer
* Liquid files used: 
    * **popups.liquid** the div with class 'popup-cookie' for the cookie notice
    * **header.liquid** for the cart drawer popup, div with id 'dropdown-cart'
    * **message-modal.liquid** for the popup when adding a new item to the cart
* SCSS files used: popups.scss

## Footer and instagram part
* Liquid files used: 
    * **collection-grid-builder.liquid** for the instagram header on Home, Catalog
    * **home-heading.liquid** for the instagram header on About, Contact
    * **home-instagram.liquid** for where the instagram photos should be 
    * **footer.liquid** for the actual footer
* SCSS files used: header-and-footer.scss


# HOME PAGE
* Liquid files used:
    * **index.liquid** is the template file for this page
    * **home-grid-builder.liquid** for the slider on top of the page
    * **builder-promobox.liquid** for the rest of the sections (these might be easiest to change through the customizer)
* SCSS files used:
    * **sliders.scss** for the carousel on the top of the page
    * **home.scss** for the rest of the sections


# CATALOG PAGE
* Liquid files used:
    * **collection.liquid** is the template file for this page
    * **home-grid-builder.liquid** for the slider/banner container on top of the page
    * **buider-slideshow.liquid** for the slides (li elements)
    * **collection-leaf-webrika.liquid** is the section under the banner
    * **collection-template-webrika** in snippets for the main content including the sidebar
    * **collection-template-webrika** in sections for only the sidebar content
    * **collection-template1-webrika** in sections for the products, including the counter element
* SCSS files used:
    * **sliders.scss** for the carousel on the top of the page
    * **product.scss** for the rest of the sections (sidebar and product grid)


# SINGLE PRODUCT PAGE
* Liquid files used: 
    * **product.liquid** is the template file for this page
    * **product-template.liquid** includes the scripts and the variant of the product
    * **product-v7.liquid** the actual template for the product
    * **swatch(-1, -2).liquid** for the product variants
    * **related-products-by-tags.liquid** for the related products section
    * **product-item-new.liquid** for the single product in the carousel
    * **delivery-returnf**
    * **product-description-tabs**
* SCSS files used: 
    * **product.scss**
    * **related-products-carousel.scss**

# ABOUT PAGE
* Liquid files used:
    * **page.aboutus.liquid** is the template file for this page
    * **aboutus-grid-builer.liquid** is the builder for the main content
    * **builder-promobox** in snippets for the four boxes on the page (these might be easiest to change through the customizer)
* SCSS files used: **about.scss**

# CONTACT US PAGE 
* Liquid files used:
    * **page.contact.liquid** is the template file for this page
    * **contact-template.liquid** is the builder for the main content
* SCSS files used: **contact.scss**

# WELCOME, UNDER CONSTRUCTION AND 404 PAGES
* Liquid files used:
    * **page-welcome.liquid** in sections for the Welcome page
    * **page-under-contruction1.liquid** in sections for the Under construction page
    * **404-grid-builder.liquid** for the 404 page + builder-promobox.liquid
* SCSS files used: **welcome-under-constr-404-page.scss**

# CART PAGE
* Liquid files used:
    * **cart.liquid** for the layout
* SCSS files used: **cart.scss**