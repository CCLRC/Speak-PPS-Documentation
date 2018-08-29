# Plugin Documentation

Speak PPS is a WordPress plugin designed to save the API key, Organization Name, in the wp-options table.
The plugin also sets a cookie for every user the visits the Wordpress site.
The cookie is unique to every user.

The Organization name is to be sent with every request to PPS.
This is saved as `speak_pps_org_name` in the wp-options table.

The API key is to be used to build a signature that is sent with every request to PPS.
Details of creating this signature are in the API Documentation.
The API key is saved as `speak_pps_api_key` in the wp-options table.

The cookie value is used as a token for the user, that is to be sent with every
request, as a user identifier.
The cookie name set is `speak-pps-user`.

The Organization Name, and the API key will be requested by the client or its
agent, from PPS development team.
