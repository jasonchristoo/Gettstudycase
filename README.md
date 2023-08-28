# Gett Study Case
Study case is from https://platform.stratascratch.com/data-projects/insights-failed-orders
Finished by using Tableau

![image](https://user-images.githubusercontent.com/123045563/236743435-f981158f-3050-4a48-b70d-966354c0b343.png)

Datasets used : data_orders, being stored in a CSV format. The data_orders data set contains the following columns:

```order_datetime``` - time of the order

```origin_longitude``` - longitude of the order

```origin_latitude``` - latitude of the order

```m_order_eta``` - time before order arrival

```order_gk``` - order number

```order_status_key``` - status, an enumeration consisting of the following mapping:

  - ```4``` - cancelled by client,

  - ```9``` - cancelled by system, i.e., a reject

```is_driver_assigned_key``` - whether a driver has been assigned

```cancellation_time_in_seconds``` - how many seconds passed before cancellation


### Summary
Build up distribution of orders according to reasons for failure: cancellations before and after driver assignment, and reasons for order rejection. Analyse the resulting plot. Which category has the highest number of orders? 

>Cancellations by client is the highest result occuring specially when driver is not assigned

Plot the distribution of failed orders by hours. Is there a trend that certain hours have an abnormally high proportion of one category or another? What hours are the biggest fails? How can this be explained?

>Cancellations mostly occuring at 8 A.M. As we know this is rush hour and people tend to be in hurry.

Plot the average time to cancellation with and without driver, by the hour. If there are any outliers in the data, it would be better to remove them. Can we draw any conclusions from this plot?

>When driver is not assigned, customer tend to wait longer. It is because when driver is assigned to a customer we can look how far the driver from current location
>
>![image](https://user-images.githubusercontent.com/123045563/236977036-27a0c64d-f3c1-4361-82ef-f4555dc21b07.png)


