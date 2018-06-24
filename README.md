# ALUM
A duo of android apps that caters to both the sellers’ as well as buyers’ needs. Buyers can create a shopping list and get notified when a shop near them has any of the items from that list. Sellers can advertise for free. These ads will be custom tailored for each buyer based on his/her shopping list, interests and location. Our revenue model does not charge the buyer. The location awareness is achieved using the mobile Wi-Fi.

# Instructions to Run
For Server:
Install python bottle server: “pip install bottle” 
Make a folder named “seller_DB” in the directory where you have server.py 
Run a wifi hotspot. Update the wifi ip address in host in last line of server.py (present ip: "http://10.42.0.1:8081") 
Run the hotspot

For Android Application: 
Clone github repository Open both applications in Android Studio and change the ip in the code by changing the "Upload_URL" String at MyService, SignUPAcitvity, TodoListActivity in EasyBuy and Inventory, profileSet in LoginSignup-master.
Install Both Android Applications: "Easy Ads" and "LoginSignup-Master".
