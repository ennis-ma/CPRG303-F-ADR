# Data Storage

### Decision

- Utilize a combination of Firebase Realtime Database for real-time data syncing and WatermelonDB for offline data storage.

### Rationale

- Real-time data syncing is crucial for the interactive nature of the app, enabling users to share and receive updates promptly.
- Offline data access is essential for ensuring usability in varying network conditions, aligning with the goal of providing a seamless user experience.

### Context

- Date: October 5, 2023
- Firebase Realtime Database provides a robust, real-time data syncing solution while WatermelonDB, with its efficient querying and syncing capabilities, is well-suited for offline data storage on user devices.

### Consequences

- Ensured availability and real-time updates of data enhancing the user experience.
- Dependency on Firebase for real-time data syncing; any downtime or issues with Firebase could impact the app's functionality.
- Scheduled review one month post-development to evaluate data syncing and offline access performance, and to identify any areas for optimization.
