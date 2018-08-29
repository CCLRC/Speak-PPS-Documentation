# Plugin Documentation

Speak PPS is a wordpress plugin designed to save the API key and also set a
cookie for every user the visits the Wordpress site.
The cookie is unique to every user.

The API key is to be used to build a signature that is sent with every request to PPS. Details of creating this signature are in the API Documentation.

The cookie value is used as a token for the user, that is to be sent with every request, as a user identifier.

The API key will be requested by the client or its agent, from PPS development team.
