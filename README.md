# Experience Mod Review – Draper Smith Insurance Group

Landing page for contractors to book a free, in-person Experience Mod review.

## How requests reach you
Each request is sent as a push notification through [ntfy](https://ntfy.sh), with
**Call** and **Email** buttons in the notification.

1. Install the ntfy app (iPhone or Android) or open https://ntfy.sh/app.
2. Subscribe to the topic set in `CONFIG.ntfyTopic` near the bottom of `index.html`.

The topic name works like a password. If you ever start getting junk, change it in
`index.html` and in the app.

## Personalized links
Add URL parameters to prefill the form and greet the contractor by name:

`index.html?name=Jane%20Ortiz&company=Ortiz%20Roofing&city=Fresno&src=postcard-oct`

`src` shows up in the email so you can tell which mailer drove the request.
