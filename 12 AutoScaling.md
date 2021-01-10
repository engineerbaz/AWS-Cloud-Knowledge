# Autoscaling
Auto-scaling (Automatic Scaling) is used in cloud computing, whereby the number of computational resources in a server farm, typically measured in terms of the number of active servers, scales automatically based on the lead on the farm.
</br>


* When CPU reaches 70% then launches new EC2 Server, LB will work with ASG (AutoScaling Group) to create new resources. 
* Horizontal Scale when scaling is needed for a short period of time 
* Launch Configuration
   * Key
   * OS
   * Parameter
* ASG
   * Call LG
   * Criteria (minimum & Maximum desire ) when to create new VM
   * SNS has 3 option, EC options (Start/Stop), alert it, Launch using ASG
   * ASG will talk CloudWatch


## Benefit
* Setup Scaling 
* Automatically maintain performance 
* Make smart scaling decisions
* Fault tolerance 
   * Launching EC2 in different zones
* Increase application availability 
* Low Cost
* Choose when and how to scale
* Monitor Health Check 
* Fleet Management 
* Support multiple instance types
   * On-demand or on spot instances inside an amazon EC2  
* Launch configuration
* Life Cycle Hooks 
   * Add delay in booting instances for completing any tasks
* Terminate Lifecycle Hook. 
  



### Auto Scaling Group


* Minimum size 
   * Minimum value
* Scale-out 
* Desired Capacity 
   * Required amount 
* Maximum Size 
   * When scaling max number can be achieved 




### Scaling Policy 
* Target Tracking Scaling 
   * Modify the current capacity of the group based on a target value for a specific metric ()
* Step
   * Modify based on set of scaling adjustments
* Simple
* Scheduled
   * Time-based.