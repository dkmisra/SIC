# Summary
Smart Interface to Cloud (SIC) is a middleware that optimizes resources and budget by predicting workload. Its a client side solution that is compatible with different cloud services. Currently integrated with Amazon AWS.

# Status
Code coming soon. Please visit in couple of days.

# What is SIC and why do I needed?
Often workload is transfered to cloud, either when workload becomes too much to handle on the local system or
to benefit from specialized hardware for specific type of requests. Thus, one has to often request for cloud instances
on demand. Inspite of streamlined interface, time taken between requesting an instance to having an available ready-to-use instane can be significant (upto a minute or more). While keeping instances open all the time wastes money and resources.

To handle this problem, in situations where workload is fairly predictable, we propose a solution called SIC. SIC predicts workload and prefetches the instance so that an instance is available when you need it, while minimizing idle time of instance. Really its that simple.
