# Shipment Management Dashboard
Dashboards (for both admin and super-admin) that  will allow the admin/super admin to run CRUD operations on current orders, shipments, returns, courier services, and user/admin information.

## Order Management for an e-commerce platform

The project required an automated flow of events to manage product orders and deliveries, track initiated deliveries, and pick up requested product returns. The entire project stack was based on JavaScript.

I created APIs (both REST and SOAP, using Node JS) to:
- Identify the courier service provider (FedEx, ICS, Purolator, UPS, USPS, etc) from a given unique tracking ID and use it to track the shipment and get the live status of the respective delivery.
- Fetch tracking numbers of shipments by their references and then use the same to track their overall delivery status.
- Generate return labels and pickup requests, for product items to be returned/replaced, via popular courier service providers.

Then I created a UI (using React) to:
- List all initiated product orders with their necessary details like date, courier service used, current status, etc.
- Get details about an individual product order, get the current location using its tracking ID and also delete the order if needed
- Fetch all return requests from the database and track their progress
- Manage super admins and admins within the client's organisation ensuring different roles and privileges to each kind

Will write about this more with time. For now, the following are a few snapshots from the interface. 

![](https://raw.githubusercontent.com/subham99saha/shipment-management-dashboard/refs/heads/main/snaps/2022-04-12%20(1).png)

![](https://raw.githubusercontent.com/subham99saha/shipment-management-dashboard/refs/heads/main/snaps/2022-04-12.png)

![](https://raw.githubusercontent.com/subham99saha/shipment-management-dashboard/refs/heads/main/snaps/2022-05-24.png)

![](https://raw.githubusercontent.com/subham99saha/shipment-management-dashboard/refs/heads/main/snaps/2022-05-31%20(1).png)

![](https://raw.githubusercontent.com/subham99saha/shipment-management-dashboard/refs/heads/main/snaps/2022-05-31%20(2).png)

![](https://raw.githubusercontent.com/subham99saha/shipment-management-dashboard/refs/heads/main/snaps/2022-05-31%20(3).png)


