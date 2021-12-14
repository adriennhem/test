# Sales Forms

## Form Submission

1. Visitor navigates to the marketing website available at [https://gitbook.com](https://gitbook.com)
2. Visitor hovers over `Contact Us` in the navbar.&#x20;
3. Visitor can either select `Book a Demo` or `Contact Us.`&#x20;
4. Visitor fills in and submits the form.&#x20;
5. We display the calendar of an account executive directly if it meets certain criteria when the visitor is on the Book a Demo page.
6. The form is available in [Hubspot](https://app.hubspot.com/contacts/8443689/objects/0-1/views/5433809/list) and also notifies the `#notif-hubspot-sales-form` channel in Slack.&#x20;

{% embed url="https://www.loom.com/share/d92553cee8b643f2affffd24064737e6" %}
Form submission by a visitor
{% endembed %}

## Anatomy of a form

![HubSpot sales form notification in Slack (channel: #notif-hubspot-sales-form)](<../../.gitbook/assets/Screenshot 2021-12-07 at 10.29.40.png>)

* **Contact Owner**: the person to whom the form has been assigned to.
* **Message**: this is the content of form. It's mandatory to fill in this field.
* **Type of form**: it can either be Contact Us or Request a Demo.
* **Firmographics data**: we enrich data with Clearbit data.&#x20;

## Find the forms

* [#notif-hubspot-sales-form](https://gitbook.slack.com/archives/C01QCP9T9JT) channel in Slack
* [Hubspot](https://app.hubspot.com/contacts/8443689/objects/0-1/views/5433809/list)
