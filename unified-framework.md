# ORM like unifying-framework for every component of the tech-stack

-   Are uniform layer over all the clouds which provide the best of the best of the services.
-   for example if you need a queue service use Kaka and it would work similar to how you will use the SQS
	-   https://aiven.io/pricing

I don't remember what I was thinking at the time.

The idea was around providing a uniform interface over all the open source services, such that the services could act like a drop-in replacement of the cloud services. 

Eg: If the customers are using SQS, and they want to migrate to managed or self-hosted kafka, then all they need to do is change the adapter.