# YouTube Live Chat Store Protocol - Live Chat Data
It stores actual live chats.

## Struct
- array
    - seconds: number
    - [message_type](#message-Type): number
    - message: string
    - money (only available when type is paid)
        - price: number
        - currency: string
    - user
        - id: string
        - name: string
        - badges: array
            - [badge_type](#badge-type): number
            - [badge_status](#badge-status): number

### Message Type
|message_type|Type|
|:--|:--|
|0|Normal Message|
|1|Paid Chat (Super Chat)|
|2|Membership Notification|
|3|Paid Sticker|

### Badge Type
|badge_type|Type|
|:--|:--|
|0|Moderator|
|1|Membership|

### Badge Status
This will save badge status.
Currentry only store membership month.
