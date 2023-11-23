# Credit Lending - DE - Spec

# 📋Business Use-Case

> We are approached by one of the reputed lending partner in a business with their requirement. They lend loans to those who does not have access to normal banks. Customer’s may not have access to normal banks credit due to various reasons - poor credit score, no bank account, not meeting criteria, etc., High risks are involved while lending credits to such customers and thus lending partner need to minimize the risk.
> 

> We are approached to build an end to end analytics project which will identify the risk involved in lending loans to such customers for the lending partner to take decision. We are given the sole ownership for the development of an entire project. The part of analytics and building ML models will come later, now we have to start with the requirement gathering for building data engineering pipeline which will serve the required data for analytics and build machine learning model.
> 

# 👀 Problem

> Below are the business processes that lending partner needs to implement.
> 
1. Risk modelling of customers.
2. Automated loan origination process.
3. Minimize credit loss by proper servicing of the loans.
4. Predict any defaulters and track them for payment of EMI.

---

# 💭 Proposal

> Our project manager along with the solution architect have proposed the approach which we will be taking to achieve the required business need. It will consist of the various sprints and those sprint will consist of various tasks and sub-tasks.
> 
1. Building a Simple Data Ingestion Pipeline
2. Adding Idempotency to the Pipeline
3. Adding Unit Testing
4. Creating Multiple Pipeline on the Same Principles
5. Orchestration and Workflow Management
6. Automation of Data Pipeline
7. Data Quality & Validation
8. Continuous Integration and Continuous Deployment
9. Infrastructure as Code
10. Scalability and Optimization

---

# 📝Data Requirements and Data Engineering Goals.

> Below are the requirements of data that will support the business problem. To enable automated processing, we need to collect a lot of data.
> 
1. Customer personal information (Structured)
2. Customers' credit details (Semi-structured)
3. Customer’s employment info (Structured)
4. Location via GIS data (Semi-structured)
5. Document data (Unstructured)

> As a Data Engineer we have to ensure the following points to achieve our goal of serving data to downstream systems.
> 
1. Ingest all the above types of data
2. The ingestion process should be automated
3. It should be scalable and robust to minimize data loss
4. We need to cleanse and transform the data for business needs.
5. The data should be available for reporting within the agreed SLA.
