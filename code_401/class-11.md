# Event Driven Applications

## Review, Research, and Discussion

1. Why is access control important?

It helps developers control what users can and can't do with data etc. when using the app

2. Describe an application that would need access control.

An message board app which allows visitors to read some forums and not others, and only lets members comment and like posts and access all sites, would benefit from acl.

3. What is a role used for?

Roles are how the developer assigns CRUD capabilities to users. Each user has a role, each role is assigned the appropriate capabilities.

4. Why is role-based access control more scalable than discretionary or mandatory access control?

Assigning permissions to roles, and then roles to users, means the developer doesn't have to assign permissions to users individually, which would be difficult at scale

## Document the following Vocabulary Terms

- Authorization: determining what a user is allowed to do

- Role Based Access Control: assigns permissions to users based on their role

- Capabilities: the permissions granted to a user based on their roles
