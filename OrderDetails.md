# Order Details Page

Users can access the Order Details page by clicking on any order card from any of the tabs on Order page, it will display all order-related information for that order such as customer’s name, order ID, customer's contact details, item details, reason for rejection and order item rejection history.

On clicking on any order card in the Open or Packed tab, users will be directed to the order details page. The order details page displays key details of an order and also enables store associates to perform the certain functions. 


### Reject Orders
During peak hours or promotional events, brick-and-mortar retail locations often face increased in-store traffic, heightening the risk that the requested item for pick-up may become unavailable due to in-store purchases. In such instances, store associates may need to reject an order or reject an order partially in case the order item inventory is insufficient at the store. Partial order rejection feature can be enabled using the toggle on the settings page.

To reject an order, click on the order card in the `Open` tab to open the order details page. Click on `Reject Order` to reject the order, select an appropriate reason for rejecting the order in the pop-up window that appears and click on the `save` icon. Another pop-up will appear to confirm order rejection, select `Reject` to reject the order. 

{% hint style="info" %} Upon rejecting an item, customers will receive an email with alternate fulfillment options, and the rejected order item will be removed from your dashboard. {% endhint %}

The available reasons for rejection are:
* **Not in Stock:** If items are out of stock or exhausted at the store, the store associate can select `Not In Stock` as a reason for rejection. In that case the inventory ATP (Available to Promise) and QOH (Quantity on Hand) are set to 0 for that product for the selected store and all open orders with respective items are auto-rejected from the store.

* **No Reason:** If there is no specific reason for rejection the store associate can select `No Reason`. When a store associate selects this option, the inventory ATP and QOH is increased by the same quantity.

{% hint style="info" %} Selecting a specific issue for rejection triggers distinct inventory responses within OMS. {% endhint %}

### Customer and Payment Details 
Customer details that are mentioned on the order such as customer’s name, and contact details can be viewed and copied from this page. Along with that payment mode is also displayed on the page for store associates to know if it is a paid order or payment needs to be collected at the time of order handover. Payment method is displayed on the right side of the order details page. 

### Assign Picker
During the process of fulfilling a BOPIS order, store associates can assign and track pickers to ensure the pickers' commission eligibility. For open orders, users can assign pickers from a pop-up that will open on clicking the `Ready for Pickup` button on the order details page. In case they want to edit the picker for an order, they can do that using the `Edit` button on the order details page of a packed order.  


# Order Item Rejection History

If an item in an order is rejected, it can be viewed in the `Order item rejection history` window.This window can be accessed by clicking on the `clock` icon on the top right corner of the order details page. If an order with a single item is rejected, it will disappear from the BOPIS app and the rejected item status will be displayed in the Sales Order page of the OMS. And when the item will be re-brokered, the item rejection history will become available in the order item rejection history window. 


# Notifications

Timely notifications are vital for store associates upon the arrival of a new order. BOPIS notifications provide updates on both new and open orders within a facility, significantly improving the efficiency of order preparation and handover procedures. Notifications can be viewed within the BOPIS app by clicking on the `bell` icon on the top right corner of the Orders page. 

Store managers can customise the following notification preferences. 

	•	New Orders: Receive notifications as new orders become available for preparation at the facility.
	•	Open Orders Reminder: Receive periodic reminders for open orders at the facility, helping users stay organised.
	•	Ready for Pickup Orders Reminder: Receive reminders for orders ready for pickup at the facility, ensuring timely customer communication.

>The frequency of reminder notifications can be configured through the `Open BOPIS order notifications` job in the Job Manager app's Fulfillment category. To manage notification frequency, go to the HotWax Commerce launchpad, access the job manager app, and go to the fulfillment page from the left menu. Click on the Open BOPIS order notification button on the Notification card. A extended menu will appear on the right where you can select the run time and schedule according to your preference and click on save to regulate the reminder frequency of the notifications. Administration permissions are required for access to this feature.

Users can configure the notification settings in two ways. 
1. Users can click on the `bell` icon on the top right corner of the Orders page, this will open the Notifications page. Once they have accessed the Notifications page, they can click on the `settings` icon at the top right corner of the page and configure notification preferences.
2. Users can use the `Notification Preference` card on the Settings page of the BOPIS app. 

