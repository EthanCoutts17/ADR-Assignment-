Title: Choosing Where to store Data


## Context 

The app's requirements include supporting offline mode, push notifications, payment gateway integration, analytics tracking and  image display optimization. 
It has already been decided to develop the app as a Native application. Now, need to decide on thebest data storage to handle both offline and online data requirements.


## Decision

it was decided to use a combination of local storage for offline data and cloud-based databases for online data synchronization.

## Rationale

1.Offline Mode: The requirement to support offline mode local data storage is a must feature for the app. By storing essential data locally on the device,
users can access critical features like product browsing and order history even without an internet connection.

2.Data Security: Sensitive user data, such as order history and payment information, can be securely stored in cloud-based databases with access controls
and encryption measures. Local storage can also implement encryption for added security.

3.Cost-Efficiency: Combining local and cloud-based storage allows for the balance of cost-effectiveness. Local storage minimizes server costs for 
frequently accessed data, while cloud-based databases provide scalability without the need for extensive local storage.

## Consequences 

implementing a combination of local and cloud-based data storage involves additional complexity in data synchronization logic.
The development team needs to ensure that data integrity is maintained during synchronization and that conflicts are handled properly.

Also,data security measures, including encryption and access controls, need to be very well implemented to protect sensitive user data. 


## References 

https://firebase.google.com/docs/firestore

https://aws.amazon.com/dynamodb/

https://developer.android.com/training/data-storage

