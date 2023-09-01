GCP Introduction :

Google Cloud offers a range of IaaS, PaaS, and SaaS products to help businesses and developers build and run their applications in the cloud. Whether you need virtualized computing resources,
a platform to develop and deploy your applications, 
or ready-to-use software applications, Google Cloud has a solution that can meet your needs.

GCP service models:

IaaS provides access to resources such as virtual machines and virtual storage :
PaaS provides execution environments, application development, and deployment tools,
SaaS provides software as a service to end-users

Services offered by google :

IAAS :Products in Google Cloud:

Compute Engine: Google's flagship IaaS offering is Compute Engine, which provides virtual machines (VMs) that can be used to run a wide range of applications. Customers can choose from a variety of VM types, including general-purpose, memory-optimized, and compute-optimized instances.
Cloud Storage: Cloud Storage is a highly scalable object storage service that allows customers to store and retrieve data from the cloud. It can be used for backup and archiving, as well as for serving static content on websites.
Cloud SQL: Cloud SQL is a fully managed relational database service that supports MySQL, PostgreSQL, and SQL Server. It offers automatic backups, replication, and failover, as well as built-in security features.

PAAS :Products in Google Cloud:

App Engine: App Engine is a fully managed PaaS offering that allows developers to build and deploy web and mobile applications at scale. It supports several programming languages and frameworks, including Java, Python, Node.js, and PHP.
Cloud Functions: Cloud Functions is a serverless computing platform that allows developers to write and deploy event-driven functions that automatically respond to events in the cloud. It supports several programming languages, including Node.js, Python, and Go.
Cloud Run: Cloud Run is a fully managed container platform that allows developers to deploy containerized applications quickly and easily. It supports several programming languages and frameworks, including Java, Python, Node.js, and Ruby.

SaaS Products in Google Cloud :

Google Workspace: Google Workspace (formerly G Suite) is a suite of productivity and collaboration tools that includes Gmail, Google Drive, Google Docs, Google Sheets, and more. It allows teams to work together seamlessly and securely in the cloud.
Google Analytics: Google Analytics is a web analytics service that allows website owners to track and analyze visitor traffic and behavior. It provides insights into user behavior, traffic sources, and more, helping businesses optimize their websites for maximum effectiveness.
Google Meet: Google Meet is a video conferencing service that allows teams to collaborate and communicate in real time. It offers advanced features like screen sharing, recording, and live captions, making it a powerful tool for remote teams.
---------------------------------------------------------------------------------------------------------------------------------------------------------
IAM Roles :

This model for access management has three main parts:

Principal -  A principal can be a Google Account (for end users), a service account (for applications and compute workloads), a Google group, or a Google Workspace account or Cloud Identity domain that can access a resource. Each principal has its own identifier, which is typically an email address.
Role -  A role is a collection of permissions. Permissions determine what operations are allowed on a resource. When you grant a role to a principal, you grant all the permissions that the role contains.
Policy - The allow policy is a collection of role bindings that bind one or more principals to individual roles. When you want to define who (principal) has what type of access (role) on a resource, you create an allow policy and attach it to the resource.

Principals/identity (User account - gmail , service account , google group ), roles (admin /others to the resources ), permission(what operation to perform on the cloud resources ) -

Primitive /basic role - Owner (Add /remove mmebres and delete projects), editor (deploy application , modify codes and configure services) and viewer (view or read ) access
Predefined: Predefined roles provide finer-grain access to specific services in the Google Cloud. 
Custom: Custom roles provide finer-grain access to an organization-specific list of permissions to meet specific needs.  

---------------------------------------------------------------------------------------------------------------------------------------------------------------








