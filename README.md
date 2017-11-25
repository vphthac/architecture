# Architecture

The VPH online architecture is currently a bit of a mish-mash of different services linked togeter to give us something that kind of works.

## Memebership

### Website
Most of the membership is handled through the membership website, membership.vphthac.org.uk. 

### New Attendees

New Attendees at the club are logged to the [New Attendees spreadsheet](https://docs.google.com/spreadsheets/d/1GuBsTHh4d29wvsEuuPspq6FMnBzsUSuvwMQgCqT5jt4] through a [Google Form](https://docs.google.com/forms/d/1cHRcKl4x6JvYuN4ozPwAgfHk0MlEcvJlOMw8llmpHn8). Both the spreadsheet & form are owned by _membership@vphthac.org.uk_. 

New entries into the spreadsheet picked up by a [Zapier](https://zapier.com) Zap which marshalls the input onto the [Mandrill](https://mandrillapp.com/) API to send a welcome email using the _welcome-new-attendee_ template. Any bounced or rejected emails will be notified in the [#mandrill-bounce](https://vphthac.slack.com/messages/C85FCGLAZ/) [Slack](https://vphthac.slack.com) channel.

Access to Slack is available to everybody with an _@vphthac.org.uk_ email address.

The Zapier account for new attendees is owned by [new-attendee@vphthac.org.uk](new-attendee@vphthac.org.uk). The Zapier account for Mandrill email bounce is owned by _membership@vphthac.org.uk_.

### New Members

New Members at the club are logged to the [New Members spreadsheet](https://docs.google.com/spreadsheets/d/1GwALLeDsYZxOPD6JUvwKF3vcV23IDPGBsAIyXUOcwtA/edit#gid=1168184355] through a [Google Form](https://docs.google.com/forms/d/e/1FAIpQLSfbEMy5IsErk5_jC8aBL7tFKwzqh2rZspDewZhVhTMWv7EsAg/viewform?embedded=true&formkey=dFI4ajJNQ1pGVDE0RzlIZ2ZKZ1ZJekE6MQ). Both the spreadsheet & form are owned by _membership@vphthac.org.uk_. 

New entries into the spreadsheet picked up by a [Zapier](https://zapier.com) Zap which marshalls the input onto the [Mandrill](https://mandrillapp.com/) API to send a welcome email using the _welcome-new-member-signup_ template. Any bounced or rejected emails will be notified in the [#new-member-join](https://vphthac.slack.com/messages/C7M04HU81/) [Slack](https://vphthac.slack.com) channel.

Access to Slack is available to everybody with an _@vphthac.org.uk_ email address.

The Zapier account for new attendees is owned by [new-member-registered@vphthac.org.uk](new-member-registered@vphthac.org.uk). The Zapier account for Mandrill email bounce is owned by _membership@vphthac.org.uk_.
