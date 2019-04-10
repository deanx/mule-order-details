# Order Mule API

### To call the API from CloudHub:
  - go to [CloudHub console]
  - expand /{orderId} item at the left side of the page
    - click on the "Get" button below "/orderId"
    - click on the "Try it" button
  - fill orderId parameter with the value 1 or 2
    - Any integer value is accepted, but we have only these 2 order in the database
  - Fullfill headers
    - ClientId: 1044bd247e6744f99eeff49852c76e81
    - ClientSecret: df7cCB13dE7743d6A4454423D830d1a7

### Solution

| Tool | Role |
| ------ | ------ |
| Anypoint Design Center | API-First approach
| Anypoint Exchange | Asset sharing
| Anypoint API Manager | Manage APIs (policies, versions, etc)
| Anypoint Runtime Manager | Manage Deployment (packages, properties, etc)
| AWS RDS Aurora MySQL | Cloud database solution
| Anypoint Studio | Mulesoft IDE
| MUnit | Mulesoft testing framework
| Mule 4.1.4 | Mule runtime version

[CloudHub Console]: <http://mbshop.us-e2.cloudhub.io/console/>
