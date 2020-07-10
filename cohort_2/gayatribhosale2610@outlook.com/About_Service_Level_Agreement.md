# June 16, 2020

# What is Service Level Agreement?

A Service Level Agreement (SLA) is the bond for performance negotiated between the cloud services provider and the client. Earlier, 
in cloud computing all Service Level Agreements were negotiated between a client and the service consumer. Nowadays, with the
initiation of large utility-like cloud computing providers, most Service Level Agreements are standardized until a client becomes a
large consumer of cloud services. 

#### Service level agreements are also defined at different levels which are mentioned below:

* Customer-based SLA
* Service-based SLA
* Multilevel SLA

Few Service Level Agreements are enforceable as contracts, but mostly are agreements or contracts which are more along the lines of 
an Operating Level Agreement (OLA) and may not have the restriction of law. It is fine to have an attorney review the documents
before making a major agreement to the cloud service provider. 

#### Service Level Agreements usually specify some parameters which are mentioned below:

1. Availability of the Service (uptime)
2. Latency or the response time
3. Service components reliability
4. Each party accountability
5. Warranties

In any case, if a cloud service provider fails to meet the stated targets of minimums then the provider has to pay the penalty to 
the cloud service consumer as per the agreement. So, Service Level Agreements are like insurance policies in which the corporation
has to pay as per the agreements if any casualty occurs.
Microsoft publishes the Service Level Agreements linked with the Windows Azure Platform components, which is demonstrative of
industry practice for cloud service vendors. Each individual component has its own Service Level Agreements.

#### Below are two major Service Level Agreements (SLA) described:

## 1. Windows Azure SLA –

Window Azure has different SLA’s for compute and storage. For compute, there is a guarantee that when a client deploys two or more
role instances in separate fault and upgrade domains, client’s internet facing roles will have external connectivity minimum 99.95% 
of the time. Moreover, all of the role instances of the client are monitored and there is guarantee of detection 99.9% of the time
when a role instance’s process is not runs and initiates properly.

## 2. SQL Azure SLA –

SQL Azure clients will have connectivity between the database and internet gateway of SQL Azure. SQL Azure will handle a “Monthly
Availability” of 99.9% within a month. Monthly Availability Proportion for a particular tenant database is the ratio of the time 
the database was available to customers to the total time in a month. Time is measured in some intervals of minutes in a 30-day 
monthly cycle. Availability is always remunerated for a complete month. A portion of time is marked as unavailable if the customer’s
attempts to connect to a database are denied by the SQL Azure gateway.


Service Level Agreements are based on the usage model. Frequently, cloud providers charge their pay-as-per-use resources at a premium 
and deploy standards Service Level Agreements only for that purpose. Clients can also subscribe at different levels that guarantees
access to a particular amount of purchased resources. The Service Level Agreements (SLAs) attached to a subscription many times offer
various terms and conditions. If client requires access to a particular level of resources, then the client need to subscribe to a 
service. A usage model may not deliver that level of access under peak load condition.

## Benefits of the SLA

- Protects both parties. When internal IT deploys a new application, they work closely with end users to make sure everything isworking.
They track application success by emails and phone calls, and if there is a problem they get on the phone with the vendor to solve it. 
However, it doesn’t work like that with a business customer and their cloud provider. An SLA details expectations and reporting, so the
customer knows exactly what to expect and what everyone’s responsibilities are.

- Guarantees service level objectives. The cloud provider agrees to the customer’s SLOs and can prove it reached them. If there is a 
problem, then there is a clear response and solution mechanism. This also protects the provider. If a customer saved money by agreeing 
to a 48-hour data recovery window for some of their applications, then the provider is entirely within its rights if it takes 47 hours.

- Quality of service. The customer does not have to guess or assume levels of service. They get frequent reports on the metrics that are
meaningful to them. And if the cloud computing provider fails an agreement, then the customer has recourse via negotiated penalties.
Although these penalties will not necessarily replace lost revenue, they can be excellent motivators when the cloud computing provider
is paying $3,000 a day while a service is down.
 
 
# Date: June 20, 2020

# What is Uptime? 

Uptime simply means the duration for which any equipment or system will remain active or function properly. Similarly, in the cloud hosting services, by uptime we mean the time for which you will be able to access Cloud network system or you will be able to get advantages of cloud service.

Different cloud hosting service providers offer different Cloud Uptime. Suppose a cloud service provider offers 99.5% Cloud Uptime. This means that the cloud server will function well for the complete year, except 1.83 days. However, Cloud Uptime promise does not include server maintenance time and scheduled outage.

-----------

# What is Downtime (cloud service)?

Downtime is a period of time in which the service is unavailable or not working due to unexpected circumstances such as outages, maintenance activities or updating periods.

With the advent of virtualization and cloud computing services, a consistent and all-round service is a necessity. Customers who are looking for cloud services would only be convinced if the cloud solution is promised to perform better instead of an on-premise solution. Downtime or availability is considered to be one of the most important factors to consider when implementing a new cloud service to the solution lineup.

------------

# Date: June 21, 2020

# What is serverless computing?

Serverless is an approach to computing that offloads responsibility for common infrastructure management tasks (e.g., scaling, scheduling, patching, provisioning, etc.) to cloud providers and tools, allowing engineers to focus their time and effort on the business logic specific to their applications or process.

The most useful way to define and understand serverless is focusing on the handful of core attributes that distinguish serverless computing from other compute models, namely:

- The serverless model requires no management and operation of infrastructure, enabling developers to focus more narrowly on code/custom business logic.

- Serverless computing runs code only on-demand on a per-request basis, scaling transparently with the number of requests being served.

- Serverless computing enables end users to pay only for resources being used, never paying for idle capacity.

- Serverless is fundamentally about spending more time on code, less on infrastructure.

![](https://blog.runcloud.io/wp-content/uploads/2019/07/serverlessComputingBanner.jpg)

## Serverless architectures pros and cons

### Pros

While there are many individual technical benefits of serverless computing, there are four primary benefits of serverless computing:

- It enables developers to focus on code, not infrastructure.

- Pricing is done on a per-request basis, allowing users to pay only for what they use.

- For certain workloads, such as ones that require parallel processing, serverless can be both faster and more cost-effective than other forms of compute.

- Serverless application development platforms provide almost total visibility into system and user times and can aggregate the information systematically.

### Cons

While there is much to like about serverless computing, there are some challenges and trade-offs worth considering before adopting them:

- **Long-running processes:** FaaS and serverless workloads are designed to scale up and down perfectly in response to workload, offering significant cost savings for spiky workloads. But for workloads characterized by long-running processes, these same cost advantages are no longer present and managing a traditional server environment might be simpler and more cost-effective.

- **Vendor lock-in:** Serverless architectures are designed to take advantage of an ecosystem of managed cloud services and, in terms of architectural models, go the furthest to decouple a workload from something more portable, like a VM or a container. For some companies, deeply integrating with the native managed services of cloud providers is where much of the value of cloud can be found; for other organizations, these patterns represent material lock-in risks that need to be mitigated.

- **Cold starts:** Because serverless architectures forgo long-running processes in favor of scaling up and down to zero, they also sometimes need to start up from zero to serve a new request. For certain applications, this delay isn’t much of an impact, but for something like a low-latency financial application, this delay wouldn’t be acceptable.

- **Monitoring and debugging:** These operational tasks are challenging in any distributed system, and the move to both microservices and serverless architectures (and the combination of the two) has only exacerbated the complexity associated with managing these environments carefully.

## Data processing

Serverless is well-suited to working with structured text, audio, image, and video data around tasks that include the following:

- Data enrichment, transformation, validation, cleansing
- PDF processing
- Audio normalization
- Image rotation, sharpening, and noise reduction
- Thumbnail generation
- Image OCR’ing
- Applying ML toolkits
- Video transcoding

## advantages of serverless computing

- **Lower costs -** Serverless computing is generally very cost-effective, as traditional cloud providers of backend services (server allocation) often result in the user paying for unused space or idle CPU time.

- **Simplified scalability -** Developers using serverless architecture don’t have to worry about policies to scale up their code. The serverless vendor handles all of the scaling on demand.

- **Simplified backend code -** With FaaS, developers can create simple functions that independently perform a single purpose, like making an API call.

- **Quicker turnaround -** Serverless architecture can significantly cut time to market. Instead of needing a complicated deploy process to roll out bug fixes and new features, developers can add and modify code on a piecemeal basis.
