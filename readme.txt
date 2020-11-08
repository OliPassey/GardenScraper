GardenScraper by Django Claughan claughandjango@gmail.com

This script will create a WooCommerce product for your online bookshop from a Gardeners product url.

### INSTRUCTIONS ###

1. Use the instructions from the link below to generate a consumer key and consumer secret for your WooCommerce shop
	https://docs.woocommerce.com/document/woocommerce-rest-api/#section-2
	Remember these details as they will be inaccesible once you close the page.

2. Open the SETUP.txt file and add your Gardeners login details as well as the consumer key and consumer secret that you just generated.
	The shop url should lead to the homepage of the website your online shop is on.
	Make sure you don't change the formatting of this file in any way by adding extra lines etc.
	Save changes and close the file. You will only need to do this the first time you run the program.
	Make sure SETUP.txt is in the same folder as GardenScraper.exe before running the program.

3. Run GardenScraper.exe, it may take a short while to load text. the program will display the details you added to SETUP.txt 
	and ask for a Gardeners product url. Paste the url of the book you want to add and hit enter.

4. The program will display the details found from Gardeners, then a large block of text showing the information sent to your
	WooCommerce shop.

5. The program will ask if you want to add another product. Entering 'y' will ask you to enter another url, and entering 'n'
	will close the program.