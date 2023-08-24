# Broken Access Control

Broken Access Control is a critical security vulnerability that occurs when an application doesn't properly enforce restrictions on what authenticated users are allowed to do. This can result in unauthorized access to certain functionalities, data, or resources within the application. Essentially, it means that users are able to bypass the intended access controls and perform actions they shouldn't be allowed to perform.



#  Broken access control vulnerabilities examples

1. **Vertical Privilege Escalation**:
   - **Example**: A regular user is able to access administrative functions by manipulating a URL parameter.

2. **Horizontal Privilege Escalation**:
   - **Example**: User A is able to access or modify data belonging to User B due to insufficient session isolation.

3. **Direct Object References**:
   - **Example**: Changing a URL parameter to access another user's profile or private data that should not be accessible.

4. **Insecure Access to APIs**:
   - **Example**: An API endpoint doesn't require proper authentication, allowing unauthorized users to retrieve sensitive information.

5. **Insecure Direct Object References (IDOR)**:
   - **Example**: Manipulating parameters to access files or records that aren't intended for public access, such as accessing another user's invoice by changing the invoice ID in the URL.

6. **Missing Function Level Access Control**:
   - **Example**: A hidden functionality accessible via a URL that wasn't properly protected, allowing unauthorized users to perform specific actions.

7. **Unprotected URL Paths**:
   - **Example**: Failing to enforce access controls on certain URL paths, allowing unauthorized access to certain resources.

8. **Privilege Escalation via Parameter Tampering**:
   - **Example**: Changing a numeric value in the URL to manipulate the scope of a user's access, such as changing a "role" parameter from "user" to "admin."

9. **Insecure State Transitions**:
   - **Example**: An application doesn't properly check the user's current state or context, allowing them to perform actions they shouldn't be able to based on their current state.

10. **Overly Permissive Access Controls**:
    - **Example**: Giving users broader access privileges than necessary due to misconfigured roles or groups.

11. **Insecure Business Logic**:
    - **Example**: Exploiting flaws in the application's logic to perform unauthorized actions, such as skipping a required step in a workflow.

12. **Predictable Resource Locations**:
    - **Example**: An attacker can guess the URL of a sensitive resource due to a predictable naming convention.

13. **Insecure Cross-Account Access**:
    - **Example**: In a multi-tenant environment, one user gains access to another user's resources because of misconfigured access controls.

14. **Insecure Access Control Defaults**:
    - **Example**: Default settings provide broader access than necessary, and administrators fail to customize them.

