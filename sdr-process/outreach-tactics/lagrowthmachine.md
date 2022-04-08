# 🔥 LaGrowthMachine

## What is it?&#x20;

We use LaGrowthMachine (LGM) to run multichannel sequences. You can build a sequence including email, LinkedIn (including voice notes) and Twitter touches.

Check out their help center for info on how it works and answers to common questions 👇

{% embed url="https://help.lagrowthmachine.com/en" %}
LGM Help Center
{% endembed %}

## How does it work?

It works by connecting your LinkedIn & Gmail accounts (and Twitter if you're into that), into a LGM Identity. This Identity is then used to automatically reach out to your leads via the channels you choose.&#x20;

#### The LGM Widget

During set-up you need to [install the LGM widget](https://lagrowthmachine.com/download/mac) on your computer. The widget essentially runs a virtual machine which automates the tasks.&#x20;

![](<../../.gitbook/assets/Screenshot 2022-04-08 at 11.54.08 AM.png>)

{% hint style="danger" %}
Automation of your tasks only happens when the Widget is open and running! This means if your laptop is sleeping, you're not automating. If you're travelling / offline for whatever reason, you can assign your identity to someone else’s widget [here](https://app.lagrowthmachine.com/settings/widget).
{% endhint %}

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

LGM will enrich your leads when they are first added to a sequence. Most importantly it will find their LinkedIn profile and attempt to find their phone number. The phone number will only be found if you're connected with them on LinkedIn AND they are sharing their number on there.&#x20;

For the enrichment to work you must have their first and last name, company name or company domain.

## Building a sequence

You can see the team's existing sequences in LGM (it's the paper plane ✈️ symbol in the left nav bar). A good idea to start is by duplicating one of these and editing it.&#x20;

LGM run a group onboarding webinar every Tuesday. I highly recommend you attend it. RSVP to the next session below 👇

{% embed url="https://app.livestorm.co/lagrowthmachine/onboarding-lgm-en?type=detailed" %}
LGM Onboarding Webinar
{% endembed %}

## How audiences work

You add leads into an Audience to enrol them into a sequence. When you build a sequence, you attach it to an Audience. When you add a lead to an Audience, it will automatically be started in any active sequences that Audience is attached to. Make sure you don't add your leads to other people's Audiences, otherwise they will be added to their sequence :)

## When a sequence ends

A lead will be taken out of a sequence when they reach a goal. By default this is when they reply to your email or LinkedIn message. You can change the goal in the sequence settings.

![](<../../.gitbook/assets/Screenshot 2022-03-23 at 7.42.06 PM.png>)

Currently there is no Calendly <> LGM integration (as far as I know), so if the lead books in with you but doesn't email you, they won't be taken out of the sequence. In this case you should go to LGM and manually pause them. I think we can build some HubSpot automation to do this for us in the future, but I don't think it's too much manual work for now.

## Send your sequence for review

You can send your sequence to the LGM team to review it. They will give you feedback on the logic/structure, and also the copy writing. This is included in our subscription and the feedback tends to be pretty useful - so I recommend doing it before you start adding leads to a new sequence.

## Auto import leads from HubSpot with Zapier

{% hint style="success" %}
Watch this [recording of a zoom training session on how to create your Zaps](lagrowthmachine.md#zapier-training-session)
{% endhint %}

You can use Zapier to auto import leads from HubSpot into your LGM Audiences. I recommend you create 1 HubSpot static list per LGM Audience, then create a Zap for each list (see diagram below). The Zap structure should be:

When a lead is added to this HubSpot List -> Add the lead to this LGM Audience

Here's a link to an example Zap like that:

{% embed url="https://zapier.com/shared/1d710ac81841c2a905cfb69e604a30cd5518d46a" %}
HubSpot to LaGrowthMachine Zap
{% endembed %}

Here's a diagram of the mapping between HubSpot lists and LGM Audiences, with the Zap in the middle. You should create 1 HubSpot List per LGM Audience, and 1 Zap for each of these pairs:

![Mapping between HubSpot lists and LGM Audiences using Zapier](<../../.gitbook/assets/Screenshot 2022-04-05 at 12.21.01 PM.png>)

#### Zapier training session

{% embed url="https://drive.google.com/file/d/1yzMFR3eltmJAggIAo42x7DRoGlgRCqcx/view?usp=sharing" %}
