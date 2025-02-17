---
title: Address collection and list growth
description: Learn what the best sources for new email addresses are, how to ensure high data quality, and alignment with legal guidelines. 
topics: Deliverability
kt: 7063
thumbnail: kt7063.jpg
doc-type: article
activity: understand
team: TM
exl-id: 350950dc-4703-402a-8e22-3862f4e21d52
---
# Address collection and list growth

The best sources of new email addresses are direct sources like sign-ups on your website or in physical stores. In those situations, you can control the experience to make sure it’s positive and that the subscriber is interested in getting email from your brand.

Some notes about these sign-up methods:

**Physical store** list collection can present challenges due to verbal or written address inputs causing misspelling in the addresses. Sending a confirmation email as quickly as possible after in-store sign-ups is recommended.

The most common form of **website sign-up** is “single opt-in.” It is the absolute minimum standard you should use to acquire email addresses. Single opt-in is when the holder of a specific email address grants a sender permission to send them marketing emails, usually by submitting the address via a web form or in-store signups. While it is possible to run a successful email campaign using this method, it can be the cause of some problems.

* Unconfirmed email addresses can have typos or be malformed, incorrect, or maliciously used. Typos and malformed addresses cause high bounce rates, which can and do provoke blocks issued by ISPs or IP reputation loss.

* Malicious submission of known spam traps (sometimes called “list poisoning”) can cause huge problems with delivery and reputation if the owner of that trap takes action. It’s impossible to know if the recipient truly wants to be added to a marketing list without a confirmation. This makes it equally impossible to set the recipient's expectations and can lead to increased spam complaints — and sometimes blocklisting if the collected email happens to be a spam trap.
  
For guidance on how to minimize the issues presented in both physical store and single opt-in, go to the [Data quality and hygiene](#data-quality-and-hygiene) section in this guide for the details and benefits of double opt-in.

>[!NOTE]
>
>Subscribers often use throw-away addresses, expired addresses, or addresses that aren’t theirs in order to get what they want from a website but also avoid getting added to marketing lists. When this happens, marketers’ lists result in having a high number of hard bounces, high spam complaint rates, and subscribers who don’t click, open, or positively engage with emails. It can be seen as a red flag for mailbox providers and ISPs.

## Sign-up forms

In addition to adding the fields for the data, you want to collect about your new subscribers, there are a few other things you should do with your sign-up form on the website.

* Set clear expectations with the subscriber that they’re agreeing to receive emails, what they will receive, and how often they will receive it.
* Add options allowing the subscriber to select the frequency or type of communications that they receive. These options allow you to know the subscriber’s preferences from the start so you can provide the best possible experience for your new customer.
* Balance the risk of losing the subscriber’s interest during the sign-up process by asking for as much information as possible. Things like their birthday, location, or interests help you send more customized content. Every brand’s subscribers have different expectations and tolerance thresholds, so testing is key to find the right balance for your situation.

 >[!NOTE]
 >
 > Don’t use pre-checked boxes during the sign-up process. While it can get you in trouble legally, it is also a negative customer experience.

## Data quality and hygiene

Collecting data is only part of the challenge. You must also make sure the data is both accurate and usable. You should have basic format filters in place. An email address isn’t valid if it doesn’t include an “@” or “.” for example. Be sure to not allow common alias addresses, which are also referred to as role accounts (like “info,” “admin,” “sales,” “support,” ). Role accounts can present risk because, by their nature, the recipient contains a group of people as opposed to a single subscriber. Expectations and tolerance can vary within a group, which risks complaints, varying engagement, unsubscribes, and general confusion.

Here are a few solutions to common issues you can run into with your email address data:

**[!DNL Double opt-in (DOI)]**
[!DNL Double opt-in (DOI)] is considered the best deliverability practice by most email experts. If you are having trouble with spam traps or complaints on your welcome emails, DOI is a good way to ensure that the subscriber receiving your emails has actually signed up for your email program and wants to receive your emails.

DOI consists of sending a confirmation email to the subscriber’s email address who has signed up to your email program which contains a link that must be clicked to confirm consent. With this acquisition method, if the subscriber doesn’t confirm, the sender wouldn’t send them more emails. Let new subscribers know you’re doing this on the website, encouraging them to complete the sign-up before continuing. This method does see a reduction in the number of sign-ups, but the people who do sign up tend to be highly engaged and stay for the long term. It usually results in a much higher ROI for the sender.

**Hidden field**
Applying a hidden field on your sign-up form is a great way to differentiate automated bot sign-ups from real human subscribers. Because the data field isn’t visible, hidden in the HTML code, a bot will enter data where a human wouldn’t. Using this method, you can build rules to suppress any sign-up that includes data populated in that hidden field.

**[!DNL re-CAPTCHA] is a validation method you can use to reduce the chances the subscriber is a bot and not a real person. There are various versions, some of which contain keyword identification or images. Some versions are more effective than others, and what you gain in security and deliverability issue prevention is much higher than any negative impact to conversions.

## Legal guidelines

Consult your lawyers to interpret local and national laws concerning email. Remember that email laws vary widely from among different countries and sometimes different local regions within a country.

* Be sure to collect a subscriber’s location information so that you’re compliant with the subscriber’s country laws. Without that detail, you can be limited in how you can market to the subscriber.
* Any relevant laws are determined by the location of the recipient, not the sender. So you must know and follow the laws for any country where you could have a subscriber.
* It’s often difficult to know with total certainty the subscriber's country of residence. Data provided by the customer can be out of date, and pixel location data may be inaccurate due to VPN or image warehousing, like with Gmail and Yahoo. When in doubt, it’s safest to apply the strictest possible laws and guidelines.

## Other non-recommended list collection methods

There are many other ways to collect addresses, each with its own opportunities, challenges, and drawbacks. Adobe doesn't recommend these in general, since use is often restricted via provider acceptable use policies. We will look at a few common examples, so you can learn the dangers to help you limit or avoid the risks:

**Buy or rent a list**
There are many types of email addresses out there. Primary email, work emails, school emails, secondary emails, and inactive emails to name a few. The types of addresses collected and shared out through bought or rented lists are rarely primary email accounts, which are where nearly all engagement and purchase activity occurs.

If you’re lucky, you get secondary accounts, where people look for deals and offers when they’re ready to shop for something. This usually results in low engagement levels — if any. If you are not lucky, the list is full of inactive emails, that could now be spam traps. Often, you get a mix of both secondary and inactive emails. In general, the quality of these types of lists does more harm than good to an email program. This practice is prohibited by the [Adobe Campaign Acceptable Use Policy](https://www.adobe.com/legal/terms/aup.html).

**Lists append**
These are customers who have chosen to engage with your brand, which is great. But they chose to engage through a method other than email (in-store, social media, etc.). They could not be receptive to getting an unrequested email from you and may also be concerned about how you gained their email address since they didn’t provide it. This method has a risk of turning a customer or potential customer who engaged with your brand into a detractor who no longer trusts your brand and goes to your competition instead. This practice is prohibited by the [Adobe Campaign Acceptable Use Policy](https://www.adobe.com/legal/terms/aup.html).

**Trade show or other event collection**
Collecting addresses at a booth or through another official, clearly branded method can be useful. The risk is that many events like this collect all addresses and distribute them through the event promoter or host. Which means the owners of these email addresses never requested to receive emails from your brand. These subscribers are likely to complain and mark your mail as spam, and they might not have provided accurate contact information.

**Sweepstakes**

Sweepstakes provide large numbers of email addresses quickly. But these subscribers want the prize, not your emails. They may not have even paid attention to the name of who would be reaching out to them. They are likely to complain and mark your mail as spam, and they may be unlikely to ever engage or make a purchase.

## Product specific resources

**Adobe Campaign Classic**

* [Create a subscription form with double opt-in](https://experienceleague.adobe.com/docs/campaign-classic/using/designing-content/web-forms/use-cases--web-forms.html?lang=en#create-a-subscription--form-with-double-opt-in)

**Adobe Campaign Standard**

* [Double opt-in process](https://experienceleague.adobe.com/docs/campaign-standard/using/communication-channels/landing-pages/setting-up-a-double-opt-in-process.html?lang=en#communication-channels)
