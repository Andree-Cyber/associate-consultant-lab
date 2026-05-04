# Final Recommendations

## Summary

The Active Directory implementation successfully centralizes user authentication, organizes employees by department, applies security policies, and provides shared folder access based on business roles.

This solution improves security, simplifies account management, and reduces the amount of manual work required to manage employee access.

## Recommendations

1. Continue using department-based security groups instead of assigning permissions directly to individual users.
2. Regularly review group membership to make sure employees only have access to the resources they need.
3. Enforce strong password and account lockout policies across the domain.
4. Use Group Policy to standardize workstation settings and reduce user misconfiguration.
5. Document onboarding and offboarding steps for new and departing employees.
6. Back up the domain controller and shared folders regularly.
7. Monitor failed login attempts and account lockouts for signs of suspicious activity.

## Business Value

This implementation gives the business a more secure and scalable IT environment. Employees can use centralized domain accounts, departments have controlled access to shared resources, and IT administrators can manage users and policies from one place.

## Resume Bullet

Built an Active Directory lab environment simulating a small business IT modernization project, including domain services, user/group management, Group Policy, shared folder permissions, and client workstation domain join.