Title: Handling permissions 

## Context 

The app's requirements include supporting offline mode, push notifications, payment gateway integration, analytics tracking and image display optimization.
it was already decided to develop the app as a Native application. Now, need to decide on how to handle permissions for accessing device features (e.g., camera, location) and push notifications.


## Decision

We have decided to implement fine-grained permission management for the mobile app, requiring user consent for each specific permission when accessing device features and enabling push notifications.


## Rationale 

1. Security: By requesting permissions only when needed,it will minimize potential security risks associated with unnecessary access to device features.
2. User Privacy: Fine-grained permission requests align with the principles of user privacy and data security. Users are more likely to trust an app that
    requests permissions transparently and only when necessary.
3.Customization: Implementing fine-grained permissions allows the app to request access to specific device features (e.g., camera, location) only when the
user attempts to use related functionalities within the app. This enhances the user experience by reducing initial permission requests and respecting user choices.

## Consequnces 

Implementing fine-grained permissions requires careful user interface design and user education to ensure that users understand why specific permissions are requested 
and how they benefit from granting them.

As well as,  the development team needs to handle cases where users deny permission, providing alternative user experiences or gracefully informing users of reduced
functionality due to denied/limited permissions.

## References

https://developer.android.com/guide/topics/permissions/overview

https://developer.apple.com/app-store/user-privacy-and-data-use/

