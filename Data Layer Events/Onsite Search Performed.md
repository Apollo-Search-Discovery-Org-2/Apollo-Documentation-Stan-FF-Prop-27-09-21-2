# Onsite Search Performed

### This event is part of the page load sequence, including virtual page loads in the case of single page apps, and must be pushed between the `Page Load Started` and `Page Load Completed` events.

## Javascript Code
```js
window.appEventData098765 = window.appEventData098765 || [];
appEventData098765.push({
  "event": "Onsite Search Performed",
    "onsiteSearch": {
        "keyword": {
            "multiSearchEntries": "<multiSearchEntries>",
            "searchTerm": "<searchTerm>",
            "searchType": "<searchType>"
        }
    }
});
```

## Variable Definitions

|Field|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|multiSearchEntries|string|The user's fields and values entered for multi-search.|fieldName\~phrase, sku\~12345, product name\~oak\|sku\~12345\|color\~green|||||||
|searchTerm|string|Describes the search keyword used after auto-correct, auto-complete, or keyword suggestion. |bluth, blue, red lobster|||||||
|searchType|string|Describes the domain of the search. |products, properties, articles, authors, coupons, publications|||||||



