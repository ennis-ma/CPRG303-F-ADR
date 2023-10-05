# Push Notifications

### Decision

- Utilize Firebase Cloud Messaging (FCM) for push notifications.

### Rationale

- Push notifications are crucial for a real-time experience, informing users about new updates, announcements, and assignments promptly.
- FCM is a proven, reliable solution for delivering push notifications across both iOS and Android platforms, aligning with our cross-platform approach.

### Context

- Date: October 5, 2023
- Our organization prioritizes timely and reliable communication to users. FCM's robust and scalable infrastructure aligns with this priority while minimizing additional development effort.

### Consequences

- Enhanced user engagement through timely notifications.
- Dependency on an external service (Firebase) which requires monitoring and potentially additional maintenance.
- The decision may trigger a subsequent ADR on handling notification preferences and ensuring privacy compliance in notification content.
- Scheduled review one month post-development to evaluate the effectiveness and reliability of the push notification system.
