# Product Interaction Occurred

### 

## Javascript Code
```js
window.appEventData = window.appEventData || [];
appEventData.push({
  "event": "Product Interaction Occurred",
    "product": [
        {
            "price": {
                "priceTier": "<priceTier>"
            },
            "productInfo": {
                "brand": "<brand>",
                "businessUnit": "<businessUnit>",
                "fulfillmentOptions": "<fulfillmentOptions>",
                "productID": "<productID>",
                "productLine": "<productLine>",
                "productVisualization": "<productVisualization>",
                "trademarkedTechnology": "<trademarkedTechnology>"
            }
        }
    ]
});
```

## Variable Definitions

|Field|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|brand|string|Describes the brand of a product or offering.|Ford, Chevrolet, Dodge, Levis, Columbia, Patagonia|||||||
|businessUnit|string|The business unit associated with each product.|Apparel, Shoes, Home|||||||
|fulfillmentOptions|string|The product fulfillment options available for each product to view impact on conversion.|Shipped Only, In Store Only, Local Pickup Only, In Store or Ship, Digital \(Email or Text\)|||||||
|priceTier|string|Describes the general pricing tier of a product. \(Good, Better, Best\)|Good, Better, Best, Bronze, Silver, Gold|||||||
|productID|string|Unique Identifier of a product or offering.  Must match the format of back-end systems if used as a key for import of product meta data. Most often, one level above SKU for products with SKU variants. |155, 65588, 987764448|||||||
|productLine|string|Describes the product Line of a product. |Laminate Wood, Vinyl, Hardwood, Stone, Ceramic|||||||
|productVisualization|string|Describes the visualization in which the product is presented. |Kitchen, Great Room, Bathroom, Bedroom, Custom|||||||
|trademarkedTechnology|string|Describes trademarks and\/or technical branding used to describe the product|Stainmaster, GoreTex, WeatherShield|||||||
