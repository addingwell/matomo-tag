# Matomo Server Tag

This tag allows you to set up Matomo via Server Side.

Supports both Universal Analytics and GA4 Clients.

## How do I use this tag?

This tag currently supports two events, that you can rename if needed:
- page views (default to `page_view`)
- purchase (default to `purchase`)

## Send the correct IP Address to Matomo

By default, the IP sent is the one of your GTM server. If you want to have the correct one, you must create an OAuth Token and set it in the Auth Token parameter.
