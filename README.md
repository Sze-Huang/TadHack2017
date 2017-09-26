# Tadhack Global Kuala Lumpur 2017

<p align="center"> 
  <img src="http://blog.tadhack.com/wpress/wp-content/uploads/2017/05/TADHack_Global_EMAIL_BANNER_3_green_v1.png">
</p>

# Video Call Transkript
This is the hack we did during **Tadhack Global Kuala Lumpur 2017** at Digi Communication Headquater on 23-24 September 2017.
### Special thanks to:
  #### Team Member
  - @[Sze Huang](https://github.com/Sze-Huang)
  - @[Edwin](https://github.com/edwinchoo1231)
  - @[Bee San](https://github.com/bsan94)
  - @Kok Sang 

## Dependencies
- Vidyo.io API
- Digi Two-factor authentication API
- Microsoft Azure Bing Speech API

### [Vidyo.io](https://developer.vidyo.io/documentation/4-1-16-8/getting-started)
Vidyo.io™ is a platform as a service (PaaS) that enables developers to provide high-quality, real-time video communication capabilities. The service includes the VidyoClient SDK, which provides the APIs for integrating such communication capabilities into a variety of applications and workflows.

Some of the features of Vidyo.io include:
- Multi-party audio and video conferencing
- Group chat
- Application sharing

The VidyoClient SDK offers the same APIs on all supported platforms, providing a fast learning curve and enabling rapid development on all device types.

Connecting to the Vidyo.io cloud is done by passing a token from your application through the VidyoClient SDK to the Vidyio.io cloud. The token identifies both your application and the user.


### [Digi for Developers - Beta](https://docs.google.com/document/d/1wWRcL7YIpaqDnN600ZHb14_yXtyO5bWQ2wGALmEUT9k/edit#)
Digi is a Malaysian mobile connectivity and internet services provider with over 12 million subscribers. Our ambition is to become Malaysians’ favourite digital life partner, providing relevant, personalised and engaging digital services. Digi is part of global telecommunications provider Telenor Group.

**Two-factor authentication**

GET /two-factor-authentication/msisdn

Generates a one-time use PIN and sends it to the user via SMS. PIN is a 4-digit numeric phrase.



