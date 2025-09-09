# Qlik SaaS Application

## 1. Qlik SaaS Audit Logs Application  ![alt text](https://community.qlik.com/t5/image/serverpage/image-id/81259iFADB3F4912896044/image-dimensions/121x98?v=v2)

In Qlik SaaS, there is very limited event information you can find through the management console. The only way to get the full picture of logging is to call API (i.e. GET /audits/archive) to capture the relevant information. The information returned depends on what logs are available and it might take a while to understand and to parse the information.  Some data transformation is needed to make the information meaningful and visible.

I have tried to create a Qlik Sense application that calls the API and transform all information into a single data model.

The below information has been extracted:
- User Log
- Space Log
- Space Assignment Log
- User Session
- App Reload
- App Load
- App Table Export Log
- App Export Log
- App Object Log
- App Publish Log
- App Data Updated Log
- License Assignment Log


![alt text](https://community.qlik.com/t5/image/serverpage/image-id/81260iE69B22924713D9A4/image-size/large?v=v2&px=999)

![alt text](https://community.qlik.com/t5/image/serverpage/image-id/81261iEC1260518B3D64AA/image-size/large?v=v2&px=999)

# Kongson Blog
If you like to explore more from me, please go to my blog [Kongson Technology Blog](https://kongsoncheung.blogspot.com/).


