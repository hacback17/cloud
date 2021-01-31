---
description: >-
  There is no charge to use these products up to their specified free usage
  limit. The free usage limit does not expire, but is subject to change.
---

# Lesson 1: Account Setup

![](.gitbook/assets/image%20%2855%29.png)

### GCP Free Trial:

* Billing account that does not get charged
  * Must be manually upgraded to  a paying account
  * Still requires a credit card for verification
* $300 USD credit that can last 12 months
  * "When your trial ends, your account will be paused and you'll have the option to upgrade to a paid account."
* Excellent for learning!
* "Business accounts are not eligible for the free trial."
* Has some restrictions 

### Free Trial Restrictions:

* No more than 8 vCPUs \(total simultaneous\)
* No GPUs \(video cards chips\)
* No TPUs \(custom chips for TensorFlow\)
* No Quota increases
* No crypto-mining allowed
* No SLAs
* No premium OS licenses \(e.g. Windows\)
* No Cloud Launcher products with extra usage fees

### "Always Free":

* Always free is a certain amount of different services that you can use without having to pay for it.
* "Always Free usage does not count against your free trial credits."
* Last beyond the end of the free trial

### "Always Free" Compute Highlights:

* Each day **\(24hr/day\)** you can run worth of an **f1-micro** instance in most **US** regions.
* **28hr/day** of **App Engine** runtime, in _**North America**_
* **2M/month** of **Cloud Functions** invocations \(with certain runtime/size limits\)

### "Always Free" Storage Highlights:

* Storage averaged over the month
* 5 GB of Regional Cloud Storage, including some operations
* 1 GB of Cloud Datastore storage, including some operations
* 10 GB of BigQuery storage, with 1 TB/month of query processing
* 30 GB HDD storage on GCE and AE
* 5 GB snapshot storage on GCE and AE
* 5 GB of StackDriver logs with 7-day retention

### "Always Free" Networking Highlights:

* Egress \(data going out\) to China and Australia not free!
* 1 GB/month of App Engine data egress
* 1 GB/month of Compute Engine data egress
* 5 GB/month of egress by Cloud Function invocations
* 10 GB/month of Cloud PubSub messages

### "Always Free" Other Highlights:

* 120 build-minutes/day of Google Cloud Container Builder
* 60 minutes/month of Google Cloud Speech API recognition from audio/video
* 1,000 units/month of Cloud Vision API calls
* 5,000 units/month Google Cloud Natural Language API
* Google Cloud Shell with 5 GB of persistent disk storage quota
* 1 GB of Google Cloud Source Repositories private hosting

## Billing Export

* Export must be set up per billing account
* Resources should be placed into appropriate projects
* Resources should be tagged with labels
* Billing export is not real-time
  * Delay in hours

