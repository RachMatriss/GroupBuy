

## (GroupBuy) Group Buying Responsive Shop Platform With Multi-Vendor, Multi-Language
![GroupBuy project](GrouBuy.jpg)
### New Features:

1. **Group Buying Only**:  
   Products can only be purchased through group buys, encouraging collective purchasing.

2. **Join or Create Groups**:
   - You can **join an existing group** for the product you want or **create your own group**:
     a) **Joining a group** is easy. Simply jump into the group. For private groups, you'll need a password, which can be obtained from the group owner.
     
     b) **Creating your own group** allows you to choose between public and private settings. For private groups, a password will be automatically generated and displayed in your profile.

## We Use 
* CodeIgniter 3.1.11
* Bootstrap 3.3.7
* MySql DB

## Donate
If this project helps you reduce time to develop, you can buy me a cup of coffee to continue its development. 
Thank you! :)
[![Donate](https://www.paypalobjects.com/en_US/i/btn/btn_donateCC_LG.gif)]()

## Support for the following features

1. Multi-Vendor
2. Multi-Language
3. Virtual products support
4. Multi Templates support
5. API
6. Group Buying (join or create groups with public/private options)
7. Beautiful administration with high levels of access
8. Ajax-based shopping cart
9. Orders are saved in the admin panel, with email notifications for new orders
10. Product quantity management via orders
11. Add textual pages
12. Activate and disable pages
13. File manager in administration
14. Integrated blog
15. Email subscription feature
16. Easy installation
17. Readable source code
18. Complete editing of public texts
19. Accept payments via PayPal, including PayPal sandbox testing
20. Fast-loading templates for good SEO
21. Change site colors using an easy-to-use gradient generator
22. Add multi-language cookie notifications from silktide.com for EU Cookie Law compliance
23. Multiple templates (easily create your own)
24. Bank account payments support
25. Highcharts statistics for orders
26. Discount codes
27. Available in English, Greek, Bulgarian
28. Responsive public pages, responsive administration, responsive vendor pages
29. Advanced search with treeView categories
30. Easy product management (fields for each added language, easy subcategory management)
31. Advanced sorting and product ordering
32. Group Buying (see explanation below)

## Group Buying Explanation
- Products can only be bought in groups. You can either join an existing group or create your own.
- **Joining Groups**: Public groups are open for anyone to join, while private groups require a password. Passwords can be obtained from the group owner.
- **Creating Groups**: Users can create a public or private group for a product. If private, the system generates a password that will be sent to your profile.

## Easy installation in 3 steps
1. Import `database.sql` to your MySQL database.
2. Set hostname, username, and password in `application/config/database.php`.
3. Set your site domain in `application/config/config.php` as `$config['base_url'] = 'http://yourdomain.com';`
4. Enjoy! :)

If you’re installing the project in a subdirectory (e.g., http://localhost/SHOP), set this directory in `application/config/config.php` as `$config['base_url'] = 'http://localhost/SHOP';`. Also, remove the "RewriteBase /" line from the `.htaccess` file to ensure CSS and JS files load correctly. For best results, install the platform at the root level (http://localhost), or set up a virtual host for custom directories (example: http://shop.dev -> point to localhost/shop). You can read about setting up virtual hosts here: http://goo.gl/UvpYMG

## Docker 
* more info comming soon ...
`1) sudo docker-compose build
2) sudo docker-compose ps
3) sudo docker-compose up`
  
## Login to administration with:
User: `admin`,  
Pass: `admin`

## Vendor Support
Login URL: `vendor/login`. Vendors are not supported only in the "onepage" template.
To register a new vendor, visit: `vendor/register`. Vendors must be enabled from `/admin (administration) -> Settings -> Multi-Vendor Support`.

## User Registration
User registration/login is available in the greenlabel template. (Can easily be added to other templates by copying files: `login.php`, `signup.php`, `user.php` and modifying the design). Users can track their order history.

## Screenshots of public pages
![alt text](https://raw.githubusercontent.com/kirilkirkov/Shopping-Cart-Solution-CodeIgniter/master/github/templates.png "Public Pages")

## Screenshots of vendor pages
![alt text](https://raw.githubusercontent.com/kirilkirkov/Shopping-Cart-Solution-CodeIgniter/master/github/vendors_pages.jpg "Vendor Pages")

## Screenshot of the admin panel
![alt text](https://raw.githubusercontent.com/kirilkirkov/Shopping-Cart-Solution-CodeIgniter/master/github/admin_panel4.png "Admin Panel")

### How To Write Templates
Check our wiki: https://github.com/kirilkirkov/Shopping-Cart-Solution-CodeIgniter/wiki/How-to-write-templates

### Shopping Cart Peculiarities
Learn more in our wiki: https://github.com/kirilkirkov/Shopping-Cart-Solution-CodeIgniter/wiki/Shopping-cart-peculiarities

### Multi Vendor Support
Read our wiki for details: https://github.com/kirilkirkov/Shopping-Cart-Solution-CodeIgniter/wiki/Multi-Vendor-Support

### API Documentation
Check our API documentation here: https://github.com/kirilkirkov/Shopping-Cart-Solution-CodeIgniter/wiki/API
