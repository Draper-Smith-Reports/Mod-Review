# Experience Mod Review – Draper Smith Insurance Group

Landing page for contractors to book a free, in-person Experience Mod review.

## How requests reach you
The form posts to [FormSubmit](https://formsubmit.co), which emails each request.
Settings are in the `CONFIG` block near the bottom of `index.html`:

- `notifyEmail` – where requests are emailed. After the first test submission, FormSubmit
  sends an activation link and a random alias; paste the alias here so your address
  isn't visible in the page source.
- `webhookUrl` – optional webhook (Notify, Zapier, Slack) pinged on each request.

## Personalized links
Add URL parameters to prefill the form and greet the contractor by name:

`index.html?name=Jane%20Ortiz&company=Ortiz%20Roofing&city=Fresno&src=postcard-oct`

`src` shows up in the email so you can tell which mailer drove the request.
