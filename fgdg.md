# Net Project Pricing

## Task 2: Cloud Services

### 4. 2. 1 Cloud Server

**Objective:** Comparing the cost of transitioning the franchisor’s web server to and recommending an ideal cloud service provider.

**Identified Cloud Service Providers:**
- Microsoft Azure
- Amazon Web Services (AWS)

**Specifications of Virtual Machine:**
- Region: Australia
- Operating System: Linux
- CPU: 4 vCPUs
- Memory: 8 GB RAM
- Bandwidth: 10 TB per month

**Comparison:**

| Provider             | Annual Cost (AUD) | Specifications                                                                                          |
|----------------------|-------------------|---------------------------------------------------------------------------------------------------------|
| Microsoft Azure      | (248.2*12) = 2987.08 | A4 v2 (4 Cores 8 GB RAM) x 730 Hours (Pay as you go) Linux (Pay as you go) 10 TB Bandwidth               |
| Amazon Web Services (AWS) | (195.5*12) = 2246.00 | Tenancy (Shared Instances) Operating system (Linux) Workload (Consistent Number of instances: 1). The specifications chosen at Amazon Web Services are: EC2 instance type (c6g. xlarge) pricing model: Usage (100 %) monitoring: OFF (disabled) DT Inbound: N/A (0 TB/Mo) DT Outbound: N/A (0 TB/Mo) DT Intra-Region: N/A (0 TB/Mo). |

**Detailed Comparison:**

**Microsoft Azure:**
- Annual Cost: 2987.08 AUD
- Specifications:
  - Instance Type: A4 v2 (4 Cores 8 GB RAM40 GB temporary storage)
  - Operating System: Linux (Pay as you go)
  - Bandwidth: 10 TB

**Amazon Web Services (AWS):**
- Annual Cost: 2246.00 AUD
- Specifications:
  - Instance Type: Advanced EC2 instance (c6g.xlarge)
  - Operating System: Linux (On demand plans)
  - Bandwidth: 10 TB

**Recommendation:**
Amazon Web Services (AWS) were considered because it has a considerably lower annual cost of 2246.00 AUD and especially the necessary specifications for the company’s web server of the franchisor. AWS provides accessibility and continuity of services with the added bonus of the low cost which is ideal for financial planning.

**Justification for Each Value Chosen:**

- **Region: Australia**
  - **Reason:** The Australian location is well-suited for hosting since it can create a favorable environment for those viewers accessing the website locally. There is also consideration of laxity of data sovereignty laws that may require some data to be hosted locally.

- **Operating System: Linux**
  - **Reason:** Linux is cheap, reliable, and has high efficiency which is why it takes the leading position in web server systems. It includes excellent security features and also accepts various compatible software, making it preferable for hosting web applications.

- **CPU: 4 vCPUs**
  - **Reason:** The minimum configuration of 4 vCPUs is adequate for a web host with average to high expected traffic rates on a server. This ensures the server can manage individual demands and handle peripheral duties and influx spikes without sacrificing performance.

- **Memory: 8 GB RAM**
  - **Reason:** It is recommended that the unit be equipped with not less than 8 GB of RAM to support the applications and services that are typically utilized by a web server. This helps in optimal execution and high resource utilization and availability for users accessing the website while enabling effective workload and app execution.

- **Bandwidth: 10 TB per month**
  - **Reason:** This amount of bandwidth is appropriate for a web server that has the potential to receive a great deal of traffic, such as 10 TB per month. It ensures that the server can meet data requirements by users without incurring extra costs in serving traffic, thereby acting as a buffer against high traffic intensity.
