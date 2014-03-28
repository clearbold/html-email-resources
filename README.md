HTML Email Resources
====================

HTML Email Resources, compiled by http://clearbold.com


### Blogs

* [Blog - Campaign Monitor](http://www.campaignmonitor.com/blog/)
* [Email on Acid](http://www.emailonacid.com/blog)
* [Email Wizardry](http://emailwizardry.nightjar.com.au/)
* [Litmus | Blog](https://litmus.com/blog/)

### Boilerplate

I haven't actually used any of these. (^MR)

* [Emailology](http://www.emailology.org/#1)
* [HTML Email Boilerplate](http://htmlemailboilerplate.com/)
* [Ink: A Responsive Email Framework from Zurb](http://zurb.com/ink/)
	* If you've relied on Zurb Foundation for your web projects, they've now tackled email.

### CSS (or lack thereof)

* [Bulletproof Email Background Images](http://emailbg.net/)
	* This technique (and tool to generate the necessary code) works, but Outlook 2007, 2010 and 2013 fall apart when you put two tables over the background image with `align=left` & `align=right`, which is a popular technique for responsive email design.

### Delivery Platforms - Self-hosted

* [Sendy](http://sendy.co/)

### Delivery Platforms - Third-party

* [Campaign Monitor](http://campaignmonitor.com)
* [ConstantContact](http://www.constantcontact.com/index.jsp)
	* We don't pay too much attention to ConstantContact. Last I looked a few years back, they did not support reusable templates or many of the great features offered by Campaign Monitor and MailChimp. ^MR
* [MailChimp](http://www.mailchimp.com)

### Design Galleries

* [Campaign Monitor: Email Inspiration](http://www.campaignmonitor.com/gallery/)

### Fonts & Typography

* [Creative Typography in Email: Q&A with Paul Airy (Litmus Blog)](https://litmus.com/blog/creative-typography-in-email-qa-with-paul-airy)

### Guides

* [Campaign Monitor Guides](http://www.campaignmonitor.com/guides/)
* [Campaign Monitor's "Will It Work?"](http://www.campaignmonitor.com/resources/will-it-work/)
* [MailChimp Guides](http://mailchimp.com/resources/)

### MX

* [MX Toolbox](http://www.mxtoolbox.com/SuperTool.aspx)
	* If you're setting up email records to authorize delivery networks, MX Toolbox will validate those records & their syntax.
* [How To Explain DKIM To Your Grandmother](http://www.messagesystems.com/blog/dkim-for-grandma/)

### Pre-flight - Inline CSS generators

* [Campaign Monitor: Inliner](http://inliner.cm/)
	* We've relied on Campaign Monitor's CSS inlining for years, even in emails we hand off to blast via other services. ^MR
* [Premailer](http://premailer.dialect.ca/)
  
### Responsive Email Design

* [Multi-Column Responsive Layouts (Campaign Monitor)](http://www.campaignmonitor.com/guides/mobile/responsive/)
	* I do things a bit differently here, converting my media query widths to 100% among other techniques. I'll try to get some examples posted. ^MR
* [Responsive HTML Emails: a Different Strategy](http://blog.fogcreek.com/responsive-html-emails-a-different-strategy/)
	* Fog Creek minimizes dependencies on media queries for their responsive email layout.
* [Responsive Web Design Resources](http://bradfrost.github.io/this-is-responsive/resources.html#email-design)
	* From [Brad Frost](https://github.com/bradfrost)'s "This is Responsive".

### Spam Busters

* Linked links:
	* This continues to trip me up. Linking a URL, such as [clearbold.com](clearbold.com), seems to immediately trigger spam filters. (^MR)

### Starter Templates

* Clearboldne.ws templates are in this repository. They'll need to be run through an inliner before sending. (See "Pre-flight - Inline CSS generators")

### Statistics & Data

* [The best time of day to send emails](http://www.adverblog.com/2012/10/12/the-best-time-of-day-to-send-emails-infographic/) (infographic)
* [Deployment Times](http://www.emailstatcenter.com/DeploymentTimes.html)
* [Email Still Dominates Sharing](http://blog.digg.com/post/49264812779/were-still-learning)
* [Mobile vs Desktop](https://www.pinterest.com/pin/34973334579201964/) (infographic)

### Templates

* [Campaign Monitor](http://www.campaignmonitor.com/templates/)
* [Zurb Ink Templates](http://zurb.com/ink/templates.php)

### Testing

* [Litmus](https://litmus.com/)
	* Litmus's virtual testing tools power those of many other platforms. For a while I've paid one-off fees to Campaign Monitor for access to email client screenshots. You get a lot more functionality working with Litmus directly, including the ability to live edit your code and refresh tests in supported email clients. (^MR)

### Tools

* [Campaign Monitor Subscribers Pepper for Mint](https://github.com/circa1977/sk.campaignmonitor_subscribers.pepper)
* [Campaign Monitor for SalesForce](http://blog.marketincontext.com/post/63514261547/campaign-monitor-for-salesforce-powerful-affordable)
* [Litmus Scope](https://litmus.com/scope/)
