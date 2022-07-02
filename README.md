# gcp-pca-cert
Google Cloud Platform : Professional Cloud Architect Certificate Preparation

# Regions and Zones

**_Regions_** : Specific Geogrphical location to host the resources. GCP provides 20+ regions around the world.


```
Why there are Multiple Regions?

1. High Availability [even if one Region goes down, can serve from other regions]
2. Low Latency [Access from anywhere around the world]
3. Adhere to Government regulations
```
---

**_Zones_** : To achieve Hight Availability within the same Region. Within Regions there are multiple zones. Each Region has atleast 3 or more zones.

```
Advantages

1. Hight Availability and Fault Tolerance within the same Region
2. Zones in a Region are connected with Low Latency links
```
---

**_Data Center_** : Each Zone has one or more discrete clusters [Data Centers]

---

**Example**

| regioncode  | region             | zones | zone list                                 |   |
|-------------|--------------------|-------|-------------------------------------------|---|
| asia-south1 | Mumbai, India APAC | 3     | asia-south1-a <br> asia-south1-b </br> asia-south1-c 
