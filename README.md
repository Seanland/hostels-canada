# Canadian Hostels
A List of Hostels in Canada

This JSON file is a list of specific information targeting the hostels of Canada.

Each entry will include the following information:
- Geographical Information: Latitude, Longtitude, Address and Province
- 3rd Party websites for booking (Using referral links - refer below)
- Contact Information: phone number, website and various emails (front desk, manager, etc.).

How to use the data:
TBD

## How to Contribute
- Create an issue so a contributor can make the required changes
- Make the required changes yourself and make a pull request

### Rules
- Please Mark all unknown answers as NULL

### Feature Requests!
TBD

## Structure
Below is the formatting and structure as to how each entry is to be listed:
```
[
  ...
  {
    "name":"HI Ottawa Jail",
    "website":"http://hihostels.ca/en/destinations/ontario/hi-ottawa",
    "phone":{
      "tollfree":"1-866-299-1478",
      "local":"1-613-235-2595"
    },
    "email":{
      "contact":"ottawa.jail@hihostels.ca"
    },
    "location":{
      "address":"75 Nicholas Street",
      "city":"Ottawa",
      "province":"ON",
      "postalCode":"K1N 7B9",
      "latitude":"45.424850",
      "longtitude":"-75.689000"
    },
    "beds":{
      "privateSingle":null,
      "privateDouble":null,
      "maleDorm":null,
      "femaleDorm":null,
      "mixedDorm":null
    },
    "wifi":{
      "available":true,
      "free":true,
    },
    "food":{
      "freeBreakfast":true,
      "onsiteBar":true,
      "onsiteRestaurant":false
    },
    "travel":{
      "parking":{
        "available":true,
        "free":null
      },
      "storage":{
        "lockers":true,
        "luggage":true
      }
    },
    "rental":{
      "bike":true,
      "canoe":null,
      "ski":null,
      "snowboard":null
    },
    "amenities":{
      "sharedKitchen":true,
      "laundry":true,
      "library":true,
      "commonRoomTv":true,
      "backyard":true
    },
    "checkIn":"15:00",
    "checkOut":"11:00",
    "social":{
      "twitter":"https://twitter.com/HIOttawajail",
      "facebook":"https://www.facebook.com/hiottawajail",
      "youtube":"https://www.youtube.com/user/HIOttawaJailHostel",
      "instagram":"https://www.instagram.com/hiottawajail/"
    }
  }
  ...
]
  ```

## Contributors
- [Sean Clarke](http://seanland.ca)

### Created and maintained by [Sean Clarke](http://seanland.ca)
