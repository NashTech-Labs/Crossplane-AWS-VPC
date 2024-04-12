# Crossplane-AWS-VPC
This is the TechHub temlate to create AWS resource - VPC using Crossplane.  
  
### Fields information  
1. **instanceTenancy:** Specifies the allowed tenancy of the instances launched in the VPC. (default or dedicated)    
  
2. **tags**: Specifies tags to apply to the VPC  

3. **enableDNSSupport**: Specifies whether DNS resolution is supported for the VPC (Default: true)  
  
4. **enableDNSHostnames**: Specifies whether DNS hostnames are supported for the VPC. (Default: false)  
  
5. **enableClassicLink**: Specifies whether ClassicLink is enabled for the VVPC. (Default: false)
  
6. **enableClassicDnsSupport**: Specifies whether DNS support is enabled for ClassicLink. (Default: false)  
  
7. **deletionPolicy**: Specifies the deletion policy for the VPC. It can be either 'Delete' or 'Retain'. If 'Delete' is chosen, the VPC will be retained in AWS even if it's removed from the cluster.      