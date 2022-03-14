# Matomo Server Tag

This tag allows you to set up Matomo via Server Side

## How do I use this tag?

This tag currently supports two events:
- page views (default to `page_view`)
- purchase (default to `purchase`)

It was also tested on both the Universal Analytics and GA4 Clients.

By default, the IP sent is the one of your server, if you want to have the correct one, you must create an OAuth Token and set it in the Auth Token parameter.
