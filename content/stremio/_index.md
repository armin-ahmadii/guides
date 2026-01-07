---
title: Stremio
next: first-page
toc: false
---

With just 10 minutes and three simple steps, you’ll unlock access to stream virtually any movie or show you want. Let’s get started!

{{< callout type="info">}}
**Technical Details**   
This is a practical guide to get stremio running in under **10 minutes**.

If you want the technical details and to customize it to your likings, Viren’s guide is a great starting resource: https://guides.viren070.me/stremio
{{< /callout >}}

{{< callout type="important">}}
**Let me know if a video guide would be helpful!**  
{{< /callout >}}

{{% steps %}}

### Sign Up for Subscriptions

You have **TWO** options to choose from.

**Real Debrid** -     
* Around **$6.45** CAD for 30 Days (Can be cheaper for longer)
* Accesses niche content at a faster rate (Better if all you watch is the anime or show that no one has ever heard of)
* **ONLY 1 INTERNET CONNECTION AT A TIME; OR THEY WILL BAN YOU**

**TorBox** - *honestly i think this one is better (especially if you wanna share) but they are both good options*
* Around **$4.15** CAD/month for Essential (Cheapest Plan)
* Better for mainstream content (May or may not take time to download the niche stuff)
* Sharing API Keys is allowed
* They do have a **FREE 7 Day Trial**, if you would like to test it out before committing.

------
Select which provider you will be using:

{{< tabs items="TorBox,Real Debrid" >}}

  {{< tab >}}
  1. Go to [TorBox.app](https://torbox.app/subscription?referral=5e7fe00c-5929-4255-b41a-777fc01a5fc1) and create an account.
  2. Purchase the Essential Plan ($3 USD/Month)     
  *Use my referral code for a free 7 days that will be added onto your subscription*
  3. Once purchased, head over to the TorBox Dashboard by clicking on your picture at the top right of your screen and heading over to settings. (Or by clicking [here](https://torbox.app/settings?section=account))
  4. Scroll down till you find API Key and keep it. You will need it later.
  
  {{< /tab >}}
  {{< tab >}}
  1. Go to [real-debrid.com](https://real-debrid.com) and create an account.
  2. Head over to the **Premium Offers** tab at the top.
  3. Purchase one of the memberships.
  4. Then head over to the **My Devices** tab
  5. Find your API Key here and keep it. You will need it later.

  {{< /tab >}}

{{< /tabs >}}


### Create Your Stremio Account

1. Visit [web.stremio.com/#/intro](https://web.stremio.com/#/intro) and sign up.
2. Go to the Addons section (jigsaw puzzle icon on the left).
3. Uninstall all addons except **Cinemeta** and **Local Files**.

### Configure AIOStreams
1. Download my preconfigured AIOStreams config file by clicking <a href="/AhrmStreams.json" download="AhrmStreams.json">HERE</a>.
2. Click [here](https://aiostreamsfortheweak.nhyira.dev/stremio/configure) to open AIOStreams.
3. In AIOStreams:
   * In the Save & Install section (💾 floppy disk icon), click Import, then Import Template, and select the config file you downloaded (ahrmstreams.json).
   * Select the service provider you chose earlier *(TorBox or RealDebrid)* and click **Next**
   * Put in the API Key that you took note of earlier       
   *(Found in TorBox Dashboard or RealDebrid-My Devices)*
   * Set a password, click Create, then Install, and choose Stremio Web.
{{% /steps %}}

### Congratulations! 🎉

You’re now setup to stream movies and shows from Stremio! Just [install Stremio on your devices](https://www.stremio.com/downloads) and log in to get started.
