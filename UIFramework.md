
Title: Native UI framwork for scenario 1


## Context 


The retail comany in scennario 1 wants a mobile app developed that  allows customers to browse and purchase products, view order history, 
and track deliveries, as well as a loyalty program feature. It was decided that a native mobil app was going to be developed, so we have to pick 
the best native UI framework.


## Decision 

it was decided to use platform-specific Native UI frameworks. So the frameworks that would be used would be, SwiftUI for iOS and Jetpack Compose for Android.

## Rationale

1. Performance: Native UI frameworks are optimized for their respective platforms, providing good performance. This is crucial for handling real-time product browsing, displaying product images,
  and providing smooth interactions.

2. Development Efficiency: While using platform-specific UI frameworks, modern frameworks like SwiftUI and Jetpack Compose offer a more efficient and faster way to create UI compared to
   traditional ways. This can lead to faster development and easier maintenance.

3.Platform-Specific Design: The retail app's success depends on providing users with a easy and intuitive user interface. By using SwiftUI for iOS and Jetpack Compose for Android,
we can ensure that the app adheres to a consistent and visually appealing user experience.

4.future use: Native UI frameworks are well-positioned to adapt to any future changes or advancements in the iOS and Android platforms, ensuring the long-term use of the app.

## Consequences 

Developing with platform-specific Native UI frameworks means maintaining separate codebases for iOS and Android. This may need additional development effort compared to using 
a cross-platform framework.

However, the benefits of having a good user experience and having the full platform advantages are within the scope of the comanys requirements. 

# Resources 

https://developer.apple.com/documentation/swiftui

https://developer.android.com/jetpack/compose


 
