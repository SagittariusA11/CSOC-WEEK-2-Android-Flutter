# CSoC - Flutter - Week 2

# Asynchronous code in Dart & Flutter

You must have encountered keywords like async, await and Future till now. These are very important blocks that one should comprehend.

Get this concept with this video created by Google developers themselves

[Async/Await - Flutter in Focus](https://www.youtube.com/watch?v=SmTCmDMi4BY)
[Asynchronous programming](https://dart.dev/codelabs/async-await)

For a better understanding about asynchronous code you can also watch:
[Asynchronous programming for beginners](https://www.youtube.com/watch?v=nHsxIQ9KMn0)

# Storing data locally

## Persisting Key-Value based data using SharedPreferences

There are a lot of options for storing data locally. The most basic one is using the [shared_preferences](https://pub.dev/packages/shared_preferences) plugin.

Here is a video explaining the [shared_preferences](https://pub.dev/packages/shared_preferences) plugin

[Flutter: Shared Preferences In 5 Minutes | Data Persistence](https://www.youtube.com/watch?v=uyz0HrGUamc)

And a more detailed one:
[Flutter Tutorial - Shared Preferences](https://www.youtube.com/watch?v=szOllHT1S7Y&t=395s)

or you can read this tutorial:
[Using Shared Preferences in Flutter to store data locally](https://blog.logrocket.com/using-sharedpreferences-in-flutter-to-store-data-locally/)

And what’s better than the Flutter documentations themselves :)
[Store key-value data on disk](https://flutter.dev/docs/cookbook/persistence/key-value)

Although key-value storage is easy and convenient to use, it has limitations:

- Only primitive types can be used: int, double, bool, string, and stringList.
- It’s not designed to store a lot of data.

sqflite plugin overcomes these limitations.

## Persist and Query data locally on the device with SQLite.

### What is SQLite?

Before moving any forward, you must know what exactly is SQLite. The following tutorial gives you a brief overview of the same.

[What is SQLite? Top SQLite Features You Should Know](https://www.sqlitetutorial.net/what-is-sqlite/)

### Creating a local SQLite database using [sqflite](https://pub.dev/packages/sqflite) package Flutter

Here comes the Flutter part.

There are a bunch of packages available to store data locally on the device, but the one recommended by Flutter is the "sqflite" package which is an SQLite plugin for Flutter.

Here is a short video by Flutter team explaining the sqflite package

[sqflite (Flutter Package of the Week)](https://www.youtube.com/watch?v=HefHf5B1YM0)

Now, let's read and learn about the sqflite plugin!
Here are the official docs from Flutter team
[Persist data with SQLite](https://flutter.dev/docs/cookbook/persistence/sqlite)

You can also go through the following links regarding sqflite plugin:
[SQFlite Database in Flutter](https://medium.com/@rajajawahar77/sqflite-database-in-flutter-c0b7be83bcd2)

or if you are more of a video person

[Flutter Tutorial - SQL Database Storage Using Sqlite & Sqflite CRUD | Android & iOS](https://www.youtube.com/watch?v=UpKrhZ0Hppk)

## The sqflite Alternative

sqflite is all you need for storing structured data locally therefore, explore this section only when you are done with sqflite.

### Hive

Hive is a key-value (NoSQL) based database that is much faster than sqflite.

[Hive Docs](https://docs.hivedb.dev)

A beginners tutorial to Hive

[Hive (Flutter Tutorial) - Lightweight & Fast NoSQL Database in Pure Dart](https://www.youtube.com/watch?v=R1GSrrItqUs&t=1712s)

## Bonus Task: Scheduling Local Notification

### What is difference between local notification and push notification?

Let’s learn the difference between local and push(cloud) notification

[Understanding the Advanced Features of the iOS SDK](https://www.oreilly.com/library/view/ios-components-and/9780133086898/ch09lev1sec1.html)

### Local Notification using [flutter_local_notification](https://pub.dev/packages/flutter_local_notifications)

Now for adding local notification to your app you can use [flutter_local_notification](https://pub.dev/packages/flutter_local_notifications) package.

You can get an insight on how to use it by reading these blogs:

[Flutter Local Notification](https://nitishk72.medium.com/flutter-local-notification-1e43a353877b)

[Implementing local notifications in Flutter ](https://blog.logrocket.com/implementing-local-notifications-in-flutter/)

Or if you like watching and learning:

[https://www.youtube.com/watch?v=8yJKWy9G9ew](https://www.youtube.com/watch?v=8yJKWy9G9ew)

## Submissions
