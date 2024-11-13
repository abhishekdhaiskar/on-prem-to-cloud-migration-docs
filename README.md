# on-prem-to-cloud-migration-docs
This repository documents an on-premises to AWS cloud migration project, detailing the planning, strategy, and execution involved in transforming a traditional infrastructure into a scalable, resilient, and cost-effective cloud environment. It includes architecture diagrams, migration steps, challenges faced, and the outcomes achieved.
# On-Premises to Cloud Migration Project

## Project Overview
This project involved migrating a legacy on-premises infrastructure to AWS Cloud, transforming it into a scalable, resilient, and cost-effective environment. The migration was executed to improve scalability, reduce costs, and enhance disaster recovery capabilities.

## Architecture Diagrams
Below are diagrams of the infrastructure before and after the migration:

- **Before Migration**  
  ![On-Premises Architecture](assets/on-prem-architecture.png)

- **After Migration**  
  ![Cloud Architecture](assets/cloud-architecture.png)

## Migration Strategy
We used a hybrid approach, starting with a lift-and-shift migration to quickly transfer workloads to the cloud, followed by optimizations to leverage AWS managed services.

### AWS Services Used
- **EC2**: For virtual machines hosting.
- **S3**: For scalable data storage.
- **RDS**: For managed database services.
- **VPC**: For network segmentation and security.
- **IAM**: For access control and management.

## Challenges and Solutions
- **Data Transfer Speed**: Addressed with AWS Database Migration Service to ensure efficient data replication.
- **Compatibility Issues**: Resolved by replatforming selected components to cloud-native services.

## Outcomes
The migration resulted in a 30% reduction in infrastructure costs, improved application performance, and enhanced disaster recovery capabilities.

## Additional Documentation
- [Planning](Planning.md)
- [Execution](Execution.md)
- [Testing and Validation](Testing-and-Validation.md)
- [Post-Migration](Post-Migration.md)
