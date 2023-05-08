# Gett Study Case
Study case is from https://platform.stratascratch.com/data-projects/insights-failed-orders


![image](https://user-images.githubusercontent.com/123045563/236743435-f981158f-3050-4a48-b70d-966354c0b343.png)

Datasets used : data_orders, being stored in a CSV format. The data_orders data set contains the following columns:

order_datetime - time of the order
origin_longitude - longitude of the order
origin_latitude - latitude of the order
m_order_eta - time before order arrival
order_gk - order number
order_status_key - status, an enumeration consisting of the following mapping:
4 - cancelled by client,
9 - cancelled by system, i.e., a reject
is_driver_assigned_key - whether a driver has been assigned
cancellation_time_in_seconds - how many seconds passed before cancellation
