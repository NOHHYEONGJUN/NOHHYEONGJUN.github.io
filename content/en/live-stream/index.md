---
title: My page
type: landing

sections:
  - block: markdown
    content:
      title: "Large-scale Traffic Handling<br> Live Streaming Infrastructure Development"
      subtitle: AWS
      text: |
        # OliveYoung Live Commerce 
        ![Project Logo](Project-Logo.png)
        - Access URL: https://www.olcl.shop
        - Test ID: user1 / CloudWave!
        
        <br><br><br>

        ## Project Introduction
        - **Multi-channel** live service providing 3 or more live channels
        - **Stable** live service through cloud-based traffic handling
        - Personalized service utilizing **AWS SaaS** based ML services

        <br><br>

        ## 1. Technology Stack
        1. **Infrastructure**
           - Nginx
           - Kubernetes
           - EC2

           <br>

        2. **Development**
           - Streamlit
           - SpringBoot
           - Lambda

           <br>

        3. **Database**
           - RDS
           - DynamoDB
           - S3

           <br>

        4. **CI/CD**
           - GitLab
           - Jenkins
           - ArgoCD

           <br>

        5. **Monitoring**
           - Loki
           - Prometheus
           - Grafana
           - CloudWatch

           <br>

        6. **Collaboration**
           - Notion
           - Slack

           <br><br><br>

        ## 2. Project Duration and Schedule Management
        Project Duration
           - August 12, 2024 ~ August 31, 2024

           <br>

        Schedule Management
           - Sharing progress through Notion and Slack
           - Daily morning meetings and Agile task distribution

           <br><br><br>

        ## 3. Project Differentiators
        - Central management environment for separation and isolation of development and operational environments
        - Warm Standby DR (RTO: 5min / RPO: 15min)
        - No Public Bastion → Using EC2 Instance Connect Endpoint
        - Closed CI/CD implementation
        - Shared resources between environments
        - Cost reduction to 1/25 level using thumbnails for Rekognize

        <br><br><br>

        ## 4. Overall Architecture
        ![Main Architecture](main-archi.png)

        <br><br><br>

        ## 5. IVS - Service Flow
        ![IVS Service Flow](IVS-service.png)

        <br><br><br>

        ## 6. Rekognition + Personalize - Service Flow
        ![Rekognition and Personalize Service Flow](Rekognition+Personalize.png)

        <br><br><br>

        ## 7. Monitoring
        ![Grafana Dashboard](Grafana.png)
        - Prometheus + Loki & CloudWatch

        <br><br><br>

        ## 8. Alarm
        ![Alarm System](Alarm.png)

        <br><br><br>

        ## 9-1. CI/CD Pipeline
        ![CI/CD Pipeline](CICD.png)

        <br><br><br>

        ## 9-2. Lambda Pipeline
        ![Lambda Pipeline](Lambda-pipeline.png)

        <br><br><br>

        ## 10. Load Test
        ![Load Test Results](LoadTest.png)
        - 100,000 requests/s Test using ApacheBench & JMeter

        <br><br><br>

        ## 11. Improvement Goals
        1. Monitoring Optimization
              - Transition from single Prometheus-based centralized monitoring → Metric management using Thanos (OSS)

              <br>

        2. Performance Enhancement through Cache Usage
              - RDS - Elastic Cache connection → Improving database access performance

              <br>

        3. Advanced Log Analysis
              - Using ELK stack (Elasticsearch - Logstash - Kibana) → Strengthening problem response capabilities 
---