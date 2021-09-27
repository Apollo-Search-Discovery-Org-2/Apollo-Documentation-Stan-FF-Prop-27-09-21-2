# User Signed In

### 

## Javascript Code
```js
window.appEventData098765 = window.appEventData098765 || [];
appEventData098765.push({
  "event": "User Signed In",
    "user": {
        "country": "<country>",
        "custKey": "<custKey>",
        "loginStatus": "<loginStatus>",
        "loyalty": {
            "memberStatus": "<memberStatus>"
        },
        "organizationID": "<organizationID>",
        "profileAttributesList": "<profileAttributesList>",
        "registrationStatus": "<registrationStatus>",
        "system": "<system>",
        "userType": "<userType>"
    }
});
```

## Variable Definitions

|Field|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|country|string|The country associated with this user's profile.|USA, Canada|||||||
|custKey|string|Unique identifier of a customer.  Any id's considered PII must be hashed. ||||||||
|loginStatus|string|Describes the login state of the user|logged in, logged out, guest|||||||
|memberStatus|string|Member status, level, or tier in a Loyalty program|Gold, Bronze, Platinum, Diamond, Silver|||||||
|organizationID|string|Customer Organization ID associated with website or mobile app behavior.|1234, G72345, Alaska|||||||
|profileAttributesList|string|A twice delimited string of key \/ value pairs.  Use \~ between key and value.  Use \| between pairs|homeStore\~234\|loyaltyTier\~gold\|memberSince\~2002|||||||
|registrationStatus|string|Describes the registration state of the user \(independent of sign-in state\)|registered|||||||
|system|string|Describes the system that the user is logged into.  \(rarely used\). |admin, shop, member|||||||
|userType|string|Describes the type of the user.  Often used to differentiate customers from employees or associates. |employee, guest, agent, customer|||||||



