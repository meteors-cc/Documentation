---
label: Verification
description: Learn more about our verification module.
category: Guides
authors:
    - name: "Aruuvi"
      link: "https://discord.com/users/766271467801018369"
      avatar: "https://media.discordapp.net/attachments/1155453973256474714/1262788048538832997/IMG_0309.PNG?ex=6697de84&is=66968d04&hm=099e4b5e4fc6982bdfa900726bd95596a784633739666b5944c46d36d3f23b22&=&format=webp&quality=lossless&width=432&height=669"
date: 2024-07-16
---

## How does it work?

Once the Verification module is enabled, users joining your server will be required to verify their account before gaining access to the server. This process helps prevent spam accounts and ensures that users are genuine.

## Enabling Verification

To enable the Verification module, use the following command:

- `/verification enable <channel> <role> [log-channel]`

You can specify the channel using either the channel ID or by mentioning the channel.

The role is the one that will be assigned to users once they have verified their account. If you don't specify a role, the default role will be assigned.

Optionally, you can designate a log channel where verification logs will be sent. This is useful for tracking user verification activity.

## Disabling Verification

Disabling the Verification module is just as easy as enabling it. Simply use the following command:

- `/verification disable`

## Customizing Verification

### Embed

You can customize the Verification module by setting your own verification message. To do this, simply use the command:

- `/verification embed set`

Then, fill in the required information. This feature allows you to create a tailored message that will be displayed whenever a user tries to verify their account.

To send the embed to channel specified before use the command `/verification embed send`.

!!!
To view the current state of the message, use the command `/verification embed view`.
!!!


### Button

You can also customize the Verification module by setting your own button text. To do this, simply use the command:

- `/verification button set [label]`

Then, fill in the required information. This feature allows you to create a button with custom text that will be displayed on the verification message.

!!!
To view the current state of the button, use the command `/verification button view`.
!!!


