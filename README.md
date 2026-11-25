# Project 5: Secure Linux Server Permissions

## Objective
Implement Linux user and group-based file access control.

## Users
- project5_alice: Authorized user
- project5_bob: Unauthorized user

## Group
- project5_team

## Configuration
- Directory: secure-data
- Owner: root
- Group: project5_team
- Permissions: 2770

## Testing Results
- Alice can access the secure directory.
- Bob is denied access.
- Group-based access control is configured.
- Setgid permission is enabled.

## Conclusion
Successfully implemented Linux file and directory
security using users, groups and permissions.
