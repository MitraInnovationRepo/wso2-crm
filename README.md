#Prerequisitis
- WSO2 EI 6.2.0
- Salesforce Dev Account
- Read the links in resouces section

#Steps
- Download and deploy the sales force connector from https://store.wso2.com/store/assets/esbconnector/details/43e44763-0d73-4ab3-8ae9-d6f73532d164

- Copy the org.apache.synapse.salesforce.poll.class-2.0.2.jar file by building https://github.com/wso2-extensions/esb-inbound-salesforce.git to the {EI_HOME}/lib folder

- Build and deploy SalesforceNotificationCapp

#Resources
- https://ei.docs.wso2.com/en/latest/micro-integrator/references/connectors/salesforce-connectors/sf-inbound-endpoint-example/
- https://ei.docs.wso2.com/en/latest/micro-integrator/references/connectors/salesforce-connectors/sf-inbound-endpoint-configuration/