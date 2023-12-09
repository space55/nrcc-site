+++
title = "FAQ"
menu = "main"
weight = 3
+++

# Frequently Asked Questions

We sometimes get asked these questions. Here are our answers!

---

## Hardware

### What are the racks like?
We standardize on 19" racks, as is used across most datacenters worldwide.

### What kind of machine can I put in the racks?
It must be a standard 19" rack-mountable server. Your server must be able to sit in the rack alone, i.e. not using a lower server for support. You can use a shelf, so long as it does not occupy more U's than you have been allotted. We do not allow tower servers within the racks.

### What should I bring when racking my server?

You only need to bring your server, its rails, and a smile. While we may have cage nuts, it is also recommended to bring your own. We will provide the networking cables (both uplink & for the BMC), and optionally, the power cables.

### Do you label servers in the rack?

We will place a vinyl label on your server on a visible location. The label will be printed by a labelmaker, and include your membership ID number.

### How can I power cycle my machine?

Your BMC, should support remote power cycling. We do not guarantee remote switchable outlets for servers.

---

## Network 

### Are there special networking requirements for servers?

We use standard RJ45 for our 1Gb copper switches, and SFP+ optics for our 10Gb fiber switches. As long as you can use one of these standards (dependent on the rack you are placed in), you should be set. Otherwise, we ask that you program your server to auto-negotiate link speed, and utilize static addresses for its IP. We do not run DHCP.

### What kind of uplink will I have?

The uplink to other servers within the rack will either be 1Gb copper or 10Gb fiber. For fiber, you must supply the optics yourself. We use LC-LC OM4 fiber. Your connection to the greater internet is dependent on the datacenter, but is otherwise unfiltered.

### How do I get my public IP address?

When racking your server, you will be provided a public IP address by the NRCC. This address will be given in advance, and is dedicated to you.

### Do you support IPv6?

Yep! We can supply you with a /48 IPv6 subnet.

### Will I get reimbursed if the network is down?

We do not reimburse for outages. NRCC is not the right place for hosting mission-critical servers.

---

## Software

### Can I point a domain at my server?

Absolutely! Do note, however, that we do not offer domain hosting services - though other members may have such a service.

### How will I access my server's BMC?

We have a VPN in place that allows access to the BMC network as needed.

### Do you operate nameservers?

No, we do not operate nameservers at the moment.

## What can/can't I do?

### What am I allowed to host on my server at NRCC?
At NRCC, you can host anything you'd like on one of your servers - as long as it's legal and doesn't get us into trouble. If it would cause issues with our vendors or sponsors, don't do it!

### Can I send spam from my server at NRCC?

Please don't send spam from your server at NRCC. We do not want our addresses placed onto spam blacklists, as that could hurt a potential future member.

---

## Abuse

### How do you handle abuse complaints?

We take abuse complaints very seriously. Please contact us at abuse@nrcc.coop with any complaints without delay.

---

## Membership

### How can I enter the datacenter?

At the moment, members must be escorted in the datacenter by a person authorized by NRCC (and our partners) to enter.

### How do members pay for their membership or rack units?

Members are billed monthly, on the first of the month, for any and all rack units they lease. Non-hosting members are billed yearly on the anniversary of having signed up.

### Do you support direct debit?

Yep! We can support direct debit - just get in contact with one of the members of the Board to get it set up.

### Where do the fees go?

The Board does not take home any salary from NRCC. All fees are used by the organization to pay for rack space, the networking hardware to support members, and other administrative costs.

### What if I miss a payment?

If you miss a payment, please contact the board right away.

### Can I make money from servers I host at NRCC?

Yes, you can. While the organization is a nonprofit, our members are not required to be nonprofits themselves.

### Can I be a member, without hosting a server in the racks?

Of course! We would love to have you - even if you have no intention of leasing space.

### What SLA do you offer?

We do not offer an SLA for uptime of the network. If you are looking to host mission-critical services, NRCC is not the correct place. It is a community supported project, and cannot guarantee availability.

### How do you monitor uptime of the network?

While we do monitor uptime of the network through automated checks, NRCC is not the correct location for mission-critical services, and the network at NRCC should not be relied upon for important operations.

### Can NRCC host services for me on their servers?

NRCC does not host member's services. In order for a service to be hosted within NRCC, the member must either use their own hardware or find another member willing to host for them.
