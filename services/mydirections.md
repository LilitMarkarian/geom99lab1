# My personal directions request

First, explore the various options through the Directions API https://developers.google.com/maps/documentation/directions/get-directions. 

Be creative and use multiple parameters from the API documentation to earn a top grade. The rubric is listed in the bottom of the MarkDown document. 

> Tip: Can't make changes? GitHub previews MD documents by default (read-only). Start editing to make the changes for your URL and JSON response below

## Directions URL

```
[https://maps.googleapis.com/maps/api/directions/json?origin=place%5Fid%3AChIJOSsq39XyrhQRaZS1Y5PQDak&destination=place%5Fid%3AChIJm4kAdXLlrhQRHK3cqdi6dMo&alternatives=true&avoid=highways&waypoints=optimize%3Atrue%7Cplace%5Fid%3AChIJTeUsWMLzrhQRoy3Ax6oRnsU%7Cplace%5Fid%3AChIJ6wNYJJLzrhQRCT22FWo9r7I%7Cplace%5Fid%3AChIJAxQo7BvwrhQReY7QmH7AmkI%7Cplace%5Fid%3AChIJ%5FYoYfv%5FwrhQRho5ROLhtn%2D4&key=AIzaSyCM%2DWWHYHIKY%2Ddo4kquMy9Z4wQaQx51AuE]
```
Copy/paste the JSON results and save them into the empty file ```mydirections.json``` in this repository

# Additional URLs 
**Origin JSON:**
```
[https://maps.googleapis.com/maps/api/place/details/json?placeid=ChIJOSsq39XyrhQRaZS1Y5PQDak&key=AIzaSyCM%2DWWHYHIKY%2Ddo4kquMy9Z4wQaQx51AuE]
```
*Origin CID URL* --> https://maps.google.com/?q=Chrysi+Ammoudia+640+04,+Greece&ftid=0x14aef2d5df2a2b39:0xa90dd09363b59469

**Destination JSON:**
```
[https://maps.googleapis.com/maps/api/place/details/json?&placeid=ChIJm4kAdXLlrhQRHK3cqdi6dMo&key=AIzaSyCM%2DWWHYHIKY%2Ddo4kquMy9Z4wQaQx51AuE]
```
*Destination CID URL* --> https://maps.google.com/?cid=14588490532685393180

## Optional URLs

Read the Rubric to find out about what options exist to earn more marks. Here is where you can provide these additional links to place ids or other items telling a story about your chosen directions API

### Simple option:

(returns map-preferred) Maps PlaceID search: https://www.google.com/maps/place/?q=place_id:ChIJFfiCrdo4Qm0RqPwuOAVtaj8
### Efficient option

(returns JSON) API PlaceID link https://maps.googleapis.com/maps/api/place/details/json?placeid=ChIJV2BQ4laeekgRFauLvdXbFXE&key=<INSERTKEY>

  which the JSON will have a CID that can be directly used as a URL like https://maps.google.com/?cid=4569584641105657000


____
## Rubric

Note: MarkDown (.md) documents are not HTML and therefore are best viewed in the github.com website, not on the pages github.io page. Marking will occur using the github.com source. 

This is part of your first practical lab in Week 3 

1. A working URL properly documented in the MarkDown and results in the JSON file with a unique origin and destination in directions earns 50%
2. Including one to four additional functioning unique parameters from the API earns 50-70%
3. Having 3 or more functioning unique/novel and well-thought out parameters from the API earns 70-90%. Explore the API documentation for parameters we have not used.
4. Tell the story of your route. Include more than 2 "stops", and/or including additional links to display PlaceIDs on Google Maps, or other innovative presentations earns 80%-100%. 
