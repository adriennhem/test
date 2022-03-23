# LaGrowthMachine 🔥

## What is it?&#x20;

We use LaGrowthMachine (LGM) to run multichannel sequences. You can build a sequence including email, LinkedIn (including voice notes) and Twitter touches.

Check out their help center for info on how it works and answers to common questions 👇

{% embed url="https://help.lagrowthmachine.com/en" %}
LGM Help Center
{% endembed %}

## How does it work?

It works by connecting your LinkedIn & Gmail accounts (and Twitter if you're into that), into a LGM Identity. This Identity is then used to automatically reach out to your leads via email the channels you choose. During set-up you need to install the LGM widget on your computer.&#x20;

The widget essentially runs a virtual machine which automates the tasks. Automation only happens when the widget it open. Fortunately all of our identities are on the same widget so even if you don't have your computer open, if someone else in the team does, automation will continue.

<details>

<summary>Set your working hours</summary>

Automation will only happen during your working hours. Set this up in your Identity settings.

![](<../../.gitbook/assets/Screenshot 2022-03-23 at 7.04.53 PM.png>)

</details>

<details>

<summary>Add your signature</summary>

You can import your email signature from Gmail

![](<../../.gitbook/assets/Screenshot 2022-03-23 at 7.06.26 PM.png>)

</details>

## Lead Enrichment

LGM will enrich your leads. Most importantly it will find their LinkedIn profile and attempt to find their phone number. For the enrichment to work you must have their first and last name, company name or company domain.

## Building a sequence

You can see the team's existing sequences in LGM (it's the paper plane ✈️ symbol in the left nav bar). A good idea way to start is by duplicating one of these and editing it.&#x20;

LGM run a group onboarding webinar every Tuesday. I highly recommend you attend it. RSVP to the next session below 👇

{% embed url="https://app.livestorm.co/lagrowthmachine/onboarding-lgm-en?type=detailed" %}
LGM Onboarding Webinar
{% endembed %}

## How audiences work

When you build a sequence, you attach it to an Audience. When you add a lead to an Audience, it will automatically be started in any active sequences that Audience is attached to. Make sure you don't add your leads to other people's Audiences, otherwise they will be added to their sequence :)

## When a sequence ends

A lead will be taken out of a sequence when they reach a goal. By default this is when they reply to your email or LinkedIn message. You can change the goal in the sequence settings.

![](<../../.gitbook/assets/Screenshot 2022-03-23 at 7.42.06 PM.png>)

Currently there is no Calendly <> LGM integration (as far as I know), so if the lead books in with you but doesn't email you, they won't be taken out of the sequence. In this case you should go to LGM and manually pause them.

## Send your sequence for review

You can send your sequence to the LGM team to review it. They will give you feedback on the logic/structure, and also the copy writing. This is included in our subscription and the feedback tends to be pretty useful - so I recommend doing it before you start adding leads to a new sequence.

## Auto import leads from HubSpot with Zapier

You can use Zapier to auto import leads from HubSpot into your LGM Audiences. I recommend you create 1 HubSpot static list per LGM Audience. Then create a Zap for each list. The Zap structure should be:

When a lead is added to this HubSpot List -> Add the lead to this LGM Audience

Here's a link to an example Zap like that:

{% embed url="https://zapier.com/shared/1d710ac81841c2a905cfb69e604a30cd5518d46a" %}
HubSpot to LaGrowthMachine Zap
{% endembed %}
