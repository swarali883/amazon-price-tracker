# amazon-price-tracker

-Find a product on Amazon that you want to track and get the product URL 
-Use the requests library to request the HTML page of the Amazon product using the URL you got above
-Use BeautifulSoup to make soup with the web page HTML you get back. You'll need to use the "lxml" parser instead of the "html.parser" for this to work.
-Use BeautifulSoup to get hold of the price of the item as a floating point number and print it out.
-So when the price is below your given lower price, then use the smtp module to send an email to yourself. In the email, include the title of the product, 
 the current price and a link to buy the product.
-Make sure you've got the correct smtp address for your email provider
