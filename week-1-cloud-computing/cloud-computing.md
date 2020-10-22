# Cloud Computing

## Cloud computing has five characteristics:

![](../.gitbook/assets/image%20%289%29.png)

1. On-demand and Self-service
   * No human intervention needed to get resources. Customers using the automated interface get processing power, storage and the network they need without the typical complex configuration.
2. Broad network access
   * Access from anywhere
3. Resource pooling
   * Providers share resources to consumers. Resources are available at multiple locations, you just need to decide where to get the resource from.
4. Rapid elasticity
   * Get more resources quickly as needed
5. Measured service
   * Pay only for what you use

![](../.gitbook/assets/image%20%282%29.png)

##  Why Cloud over Traditional Architecture?

Cloud computing is essentially the continuation of a model that rent out computing infrastructure and have it managed by dedicated professionals.

## IaaS, PaaS, SaaS

![Cloud Computing solutions. Photo credit: https://www.bmc.com](../.gitbook/assets/image%20%283%29.png)

**IaaS** - With IaaS, the services provides the underlying architecture you to run servers.

* **CPU**, **memory**, **storage**, and **networking** is provided as a service.
* The **user** needs to **manage the OS** and **the application**.

**PaaS** - The entire platform is provided to you as a service. All you need to provide is your **application**.

* The platform is a managed service.
* All the user provides is the **application** and **data**.
* Example -  AWS Elastic Beanstalk, Windows Azure, Heroku, Force.com, Google App Engine, Apache Stratos, OpenShift

**SaaS -** The platform and application is provided to you. All you need to do is to bring your data to the system.

* The platform and software is provided as a service to the user.
* The user supplies the data.
* Examples - SAP, Salesforce, G-Suite, Dropbox, Salesforce, Cisco WebEx, Concur, GoToMeeting

{% embed url="https://youtu.be/cIyYqVf3gXM" %}

##  Google Cloud Architecture

Google product and services can be broadly categorized as:

* Compute
* Storage
* Big Data
* Machine Learning
* Networking
* Operations or Tools

**Compute**: 

* Leveraging compute can include virtual machine via **Compute Engine**
* Running docker containers in the **Google's Kubernetes Engine \(GKE\)**
* Deploying applications in a managed platform like **App Engine**
* Running event-based server-less code using **Cloud Functions**

![Google&apos;s Computer Services](../.gitbook/assets/image%20%284%29.png)

**Storage:** A variety of managed storage services available as well.

* For unstructured storage -&gt; Cloud Storage
* Managed relational database -&gt; Cloud SQL or Cloud Spanner
* No-SQL database -&gt; Cloud Bigtable or Cloud Datastore

![](../.gitbook/assets/image%20%288%29.png)



![](../.gitbook/assets/image%20%285%29.png)

## Understanding Regions and Zones

Google divides the world into three multi-regional areas: 

* America
* Europe
* Asia/Pacific

![](../.gitbook/assets/image%20%287%29.png)

**"Zone** is the deployment area of the GCP. When you want to run a Virtual Machine \(VM\) in GCP, that would be placed on a zone you defined. **Region** is created using several zones. Regions are located in several geographical locations with **round trip network latency under 5ms**!! 

If you need to establish an application with high availability you should establish your application in multiple zones.That allows you to provide the service continuously without any failure.Google provides multi region resource allocation facility.Which means your resources are located at least two geographically different locations which are 160 km apart.The most important thing is you can use resources located in multiple regions for the sake of virtualization." - [Intro to GCP](https://medium.com/@sakunaj1996/google-cloud-platform-101-efbb81e7d3a6)

A zones may have one or more data centers. For example, the `us-west1` region denotes a region on the west coast of the United States that has three zones: `us-west1-a`, `us-west1-b`, and `us-west1-c`.



