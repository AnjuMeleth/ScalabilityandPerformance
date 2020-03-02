# Design for performance and scalability

## ActualCost.csv has the cost for our infrastructure

I modified the EC2 "on demand " billing option to "1yr no upfront reserved " option reducing the overall cost to <$6500 , LoweredCost.csv has the pricing details

## IncreasedPerformance.csv has the cost after improving the performance of the infrastructure. I started using EC2 dedicated hosts instead of EC2 instances and also modified the instances to be m5d with 3 yr no upfront reserved.

### terraform destroy is used to delete all the infrastructure created by terraform using .tf files