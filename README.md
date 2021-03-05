# grafana

Use these 2 CF templates to deploy Grafana server in AWS. Either using ECS Fargaye or EC2. 

For Fargate, we can define ALB in public or private subnet.
For EC2, we deploy in a private subnet and access though OpenVpn or AWS Client Vpn Endpoint.
