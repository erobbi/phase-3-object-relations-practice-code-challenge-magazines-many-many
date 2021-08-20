# Notes for this lab
## Associations
Magazine --< Subscription >-- Reader

Magazine has many Subscriptions, a Reader has many Subscriptions, and a Subscription belongs to a Magazine and to an Reader.

Magazine - Reader is a many to many relationship. (they are both many of Subscriptions)

Note: You should draw your domain on paper or on a whiteboard before you start coding. Remember to identify a single source of truth for your data.