# TTFB, which stands for Time to First Byte.

## Definition:

TTFB is the time taken between when the user first clicks a link to a page and when the first byte arrives from the server.

## TTFB is the sum of the following request phases:

1. Redirect
2. Service worker boot time, if service worker is available
3. The DNS lookup
4. The TLS or connection
5. The request time up till when the first byte arrives from the server

## TTFB score:

A good TTFB score <= 0.8 seconds for at least 75% of the users.

> TTFB is particularly important because it precedes FCP and LCP. If TTFB is high, it adds time to FCP and LCP also.

> TTFB is not a core web vital because a high or a low TTFB may not mean that a website is performing well or badly.

## Resources:

https://web.dev/articles/ttfb
