# TurboCloudFormation
2019.2.7 - The created security group is bugged. Ingress rules are not being properly applied.  CF has no errors and group appears ok in the console but there's no ingress.  To correct deploy the template then manually remove and re-add ingress
2019.6.6 - Replaced JSON w/YAML. Fixed Security Group Ingress. Added Elastic IP
2019.7.1 - removed problematic metadata
