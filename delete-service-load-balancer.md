---
copyright:
  years: 1994, 2017, 2018
lastupdated: "2018-01-24"
---

{:shortdesc: .shortdesc}
{:new_window: target="_blank"}

# Delete a Service 

After a Service has been added to a Service Group for a {{site.data.keyword.loadbalancer_short}}, it may be deleted at any time. Deleting a Service from a Service Group prevents the Service from being utilized by the {{site.data.keyword.loadbalancer_short}} unless it is manually added back to a Service Group. 

Alternatively, a Service may be disabled, which will keep the Service associated with the Service Group while making it unavailable for balancing efforts. To keep the Service associated with the {{site.data.keyword.loadbalancer_short}} Service Group, [edit the Service](edit-service-load-balancer.html) and uncheck the **Enabled** check box. 

Follow the steps below to delete the Service from the {{site.data.keyword.loadbalancer_short}}.

1. From the [Local Load Balancer Details](view-all-load-balancers.html) page, locate the service you would like to delete and expand the arrow on the left hand side.
2. Click the red 'x' at the end of the row of the Service.
3. Click **Save Configuration** at the bottom of the page for the settings to be updated.

After deleting the Service, the configuration will be saved and the changes will instantly take effect. If the deleted Service is the only one associated with a Service Group, the Group will be unable to perform any Load Balancing activities until a new Service is added.