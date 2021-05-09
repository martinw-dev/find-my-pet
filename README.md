# find-my-pet
Flutter app to give users the ability to post details of lost or found animals in their area.

## Overview
FindMyPet is a cross-platform mobile application built using Googles Flutter technology, utilising the Dart programming language. The aim of which is to give users the ability to post details of lost, spotted or found animals in their area.

Push notifications are a very important aspect of this project as it will have the biggest impact on helping to return pets home quickly and safely. With push notifications, as soon as a user creates a post about their missing a pet, all users within a given radius will receive a push notification.

The backend of this project is built using a multitude of Firebase tools:
- The Firebase authentication service is used to create and authenticate credentials for users. 
- Cloud Firestore is used as the projects database of choice.
- Firebase Storage tool is also used within this project in order to store media data, mainly images. 
- Firebase Functions are also used in order to automatically run backend code in response to predefined triggers. For the purposes of this project the functions, when triggered, send push notifications related to new posts in the user’s area or when someone comments on their post.
