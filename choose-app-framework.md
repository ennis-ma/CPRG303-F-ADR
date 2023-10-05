# Native, Web, or Hybrid App

### Decision

- We will develop a Hybrid app using the React Native framework.

### Rationale

- The university community consists of a diverse user base having different mobile operating systems (iOS and Android). A hybrid app ensures that the app is accessible to everyone irrespective of the platform they are on.
- React Native is a mature framework with a rich ecosystem, which allows for code reuse across platforms, thus accelerating the development process and reducing maintenance costs over time compared to managing two separate native codebases.

### Context

- Date: October 5, 2023
- Our team has a diverse skill set with expertise in JavaScript, which React Native leverages. This framework also aligns with our organization's priorities of cost-effectiveness and quick market delivery.
- React Native, as compared to Flutter, has been around for a longer period, and our team has prior experience with it, which makes the ramp-up time shorter.

### Consequences

- A single codebase will significantly reduce the development and maintenance time and costs.
- The app may not leverage platform-specific features or optimizations as effectively as native apps, which might slightly affect performance or user experience.
- This decision triggers the need for a subsequent ADR on the selection of a suitable UI framework within the React Native ecosystem.
- A review will be scheduled one month post-development to evaluate the performance and user satisfaction derived from the hybrid approach versus a native approach.
