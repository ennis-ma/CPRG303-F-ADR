# Permissions

### Decision

- Integration with the existing Active Directory system for authentication and role-based permissions.

### Rationale

- Leveraging Active Directory (AD) enables robust identity and access management which is paramount for securing sensitive data such as grades and personal profiles.
- AD integration will streamline the login process and ensure proper access control, aligning with organizational standards and existing infrastructure.

### Context

- Date: October 5, 2023
- The existing infrastructure of the university has Active Directory set up for managing user identities and access controls. Utilizing this existing setup is cost-effective and aligns with the organizational policies.

### Consequences

- Streamlined and secure authentication process, enhancing user experience and security.
- Dependency on the existing Active Directory setup; any changes or issues in the AD system could affect the app's authentication and authorization processes.
- The decision may trigger a subsequent ADR on the specifics of AD integration, such as handling data synchronization and ensuring real-time updates of permission changes.
