# User Signed Out

### 

## Javascript Code
```js
window.appEventData098765 = window.appEventData098765 || [];
appEventData098765.push({
  "event": "User Signed Out",
    "user": {
        "custKey": "<custKey>",
        "userType": "<userType>"
    }
});
```

## Variable Definitions

|Field|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|custKey|string|Unique identifier of a customer.  Any id's considered PII must be hashed. ||||||||
|userType|string|Describes the type of the user.  Often used to differentiate customers from employees or associates. |employee, guest, agent, customer|||||||



