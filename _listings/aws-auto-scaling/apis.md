---
name: AWS Auto Scaling
description: Auto Scaling helps you maintain application availability and allows you
  to scale yournbsp;Amazon EC2nbsp;capacity up or down automatically according to
  conditions you define. You can use Auto Scaling to help ensure that you are running
  your desired number of Amazon EC2 instances. Auto Scaling can also automatically
  increase the number of Amazon EC2 instances during demand spikes to maintain performance
  and decrease capacity during lulls to reduce costs. Auto Scaling is well suited
  both to applications that have stable demand patterns or that experience hourly,
  daily, or weekly variability in usage.nbsp;
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2_AutoScaling.png
x-kinRank: "10"
x-alexaRank: ""
tags:
- Stack Network
- Performance
- Deployment
- Compute
- Amazon Web Services
created: "2018-03-13"
modified: "2018-03-13"
url: https://raw.githubusercontent.com/streamdata-gallery/auto-scaling/master/_listings/aws-auto-scaling/apis.yaml
specificationVersion: "0.14"
apis:
- name: AWS Auto Scaling API
  description: Auto Scaling helps you maintain application availability and allows
    you to scale yournbsp;Amazon EC2nbsp;capacity up or down automatically according
    to conditions you define
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2_AutoScaling.png
  humanURL: ""
  baseURL: :///
  tags: Auto Scaling
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery/auto-scaling/master/_listings/aws-auto-scaling/action-updateautoscalinggroup-get.md
- name: AWS Auto Scaling API Update Auto Scaling Group
  description: Updates the configuration for the specified Auto Scaling group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2_AutoScaling.png
  humanURL: https://aws.amazon.com/autoscaling/
  baseURL: http:://{host}//
  tags: Auto Scaling
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/auto-scaling/master/_listings/aws-auto-scaling/action-updateautoscalinggroup-get.md
x-common:
- type: x-articles
  url: http://developer.amazonwebservices.com/connect/kbcategory.jspa?categoryID=100
- type: x-change-log
  url: http://developer.amazonwebservices.com/connect/kbcategory.jspa?categoryID=86
- type: x-code
  url: http://developer.amazonwebservices.com/connect/kbcategory.jspa?categoryID=85
- type: x-command-line-interface
  url: http://docs.aws.amazon.com/cli/latest/reference/autoscaling/index.html
- type: x-documentation
  url: http://docs.aws.amazon.com/AutoScaling/latest/APIReference/
- type: x-forum
  url: http://developer.amazonwebservices.com/connect/forum.jspa?forumID=30
- type: x-getting-started
  url: https://aws.amazon.com/autoscaling/getting-started/
- type: x-pricing
  url: https://aws.amazon.com/autoscaling/pricing/
- type: x-service-health
  url: http://status.aws.amazon.com/
- type: x-website
  url: https://aws.amazon.com/autoscaling/
- type: x-articles
  url: http://developer.amazonwebservices.com/connect/kbcategory.jspa?categoryID=100
- type: x-change-log
  url: http://developer.amazonwebservices.com/connect/kbcategory.jspa?categoryID=86
- type: x-code
  url: http://developer.amazonwebservices.com/connect/kbcategory.jspa?categoryID=85
- type: x-command-line-interface
  url: http://docs.aws.amazon.com/cli/latest/reference/autoscaling/index.html
- type: x-documentation
  url: http://docs.aws.amazon.com/AutoScaling/latest/APIReference/
- type: x-forum
  url: http://developer.amazonwebservices.com/connect/forum.jspa?forumID=30
- type: x-getting-started
  url: https://aws.amazon.com/autoscaling/getting-started/
- type: x-pricing
  url: https://aws.amazon.com/autoscaling/pricing/
- type: x-service-health
  url: http://status.aws.amazon.com/
- type: x-website
  url: https://aws.amazon.com/autoscaling/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---