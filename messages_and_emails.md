---
title: Guest Messages and Emails
tags:
  - guest messages
  - guest email
keywords: >-
  guest messages, emails, automated emails, email rules, confirmation email,
  invoice, templates, email templates
last_updated: 'December 1st, 2015'
summary: >-
  Through Guest Messages you are able to set up information and policies for
  your property, to communicate to your guests. Examples are your Cancellation
  Policy, or  Terms and Conditions. These messagages will appear in some areas
  of your Frontdesk Anywhere, like on the Booking Engine, or on your 
  Templates.  Templates are the actual messages that your guests will receive.
  Examples are Confirmation Email or Cancellation Email. 
published: true
---








   



## Guest Messages  


 - In the Admin Settings, click on the link **Guest Messages** under section _General_:  
 
![messages_1.png]({{site.baseurl}}/images/messages_1.png)



 
 - You will see different panels, each one editable and with a title on the top that should give you some guidance on what sort of information you should type in the editable box:  
 
![Guest_Messages_2.png]({{site.baseurl}}/images/Guest_Messages_2.png)


 
 - The first one is the _Invoice Message_: this is a message that will appear in each of your property invoices:    
 
![Guest_Messages_3.png]({{site.baseurl}}/images/Guest_Messages_3.png)


 
 - Proceed to edit the _Terms and Conditons_ message: the latter will show up on your Online Booking Engine, and your confirmation email:  
 
![Guest_Messages_4.png]({{site.baseurl}}/images/Guest_Messages_4.png)


 
 - The third message will be the _Room Cancellation_ message: as the text in the box says, this will appear both on your Booking Engine and in your cancellation email:  
 
![Guest_Messages_5.png]({{site.baseurl}}/images/Guest_Messages_5.png)


 
 - Finally, edit your _Guest Receipt_ and your _Registration Card_ messages:  
 
![Guest_Messages_6.png]({{site.baseurl}}/images/Guest_Messages_6.png)


 
 - When finished, scroll at the bottom of the page and click on the blue button _Save_:  
 
![Guest_Messages_7.png]({{site.baseurl}}/images/Guest_Messages_7.png)


 
## Templates   



Frontdesk Anywhere allows you to customize all communications with your guests: all templates are in a html format, and their _content_ can be easily editable!  

{{site.data.alerts.warning}} Be aware that the templates design have been built so to ensure they will render good when sent via emails on both computers and mobile devices. If you want to change the design, we do not guarantee that the template will render as good as the default ones. {{site.data.alerts.end}}  

Click [here](http://docs.frontdeskanywhere.net/build/application_resources.html) to check out all available variables you can use in the html templates!

 - In the Admin Settings, click on the blue link **Templates** under section _General_:  
 

![messages_88.png]({{site.baseurl}}/images/messages_88.png)


 
 - You will see a list of all the types of templates that the system offers: the name of each template appears on the top left hand side of each message panel.
 
![Guest_Messages_9.png]({{site.baseurl}}/images/Guest_Messages_9.png)



 
 - Under each section you will see one disabled template already listed: these templates are only used as a guidance, and they are non-editable:  
 
![Guest_Messages_10.png]({{site.baseurl}}/images/Guest_Messages_10.png)



 - To create a new template, click on the blue button _New Template_ on the top left hand side of the screen:  
 
![Guest_Messages_11.png]({{site.baseurl}}/images/Guest_Messages_11.png)


 
 - Select the template you want to create by clicking on the right option in the scroll down menu:  
 
![Guest_Messages_12.png]({{site.baseurl}}/images/Guest_Messages_12.png)


 
 - Give a name to the template and click on the blue button _Create and Edit_:  
 
![Guest_Messages_13.png]({{site.baseurl}}/images/Guest_Messages_13.png)


 
 - The template you have just created will be listed under the apposite header:  
 
![Guest_Messages_14.png]({{site.baseurl}}/images/Guest_Messages_14.png)



 
 - Once the template has been created, it also needs to be enabled. Click on the yellow button _Edit_ on the right hand side of the newly created template:  
 
![Guest_Messages_15.png]({{site.baseurl}}/images/Guest_Messages_15.png)


 
 - Enable the template by checking the box next to the tag _Template Enabled_:  
 
![Guest_Messages_16.png]({{site.baseurl}}/images/Guest_Messages_16.png)


 
 - Select where you want the template to apply and appear, by checking the right boxes under the written _System Section Filters_:  
 
![Guest_Messages_17.png]({{site.baseurl}}/images/Guest_Messages_17.png)


 
- To <span class="label label-danger">DELETE</span> a template, just click on the red button _Remove_ next to the relevant template:  

![Guest_Messages_33.png]({{site.baseurl}}/images/Guest_Messages_33.png)


 
Here is a quick breakdown of what each box means:  

If you check the box _Invoices_, your template will show up in any reservation folio, in the Invoice section of the link _Payments_:  
 
![Guest_Messages_18.png]({{site.baseurl}}/images/Guest_Messages_18.png)



 
If you check the box _POS_, the template will show up as a Receipt in the _Point of Sale_ area of your PMS:  

![Guest_Messages_19.png]({{site.baseurl}}/images/Guest_Messages_19.png)



If the box _Group Messages_ is checked, the newly create template will appear in any Group Folio, at the bottom:  

![Guest_Messages_20.png]({{site.baseurl}}/images/Guest_Messages_20.png)


 
 If you check the box _Reservation Messages_, the template will appear on the bottom left side of each reservation folio:  
 
![Guest_Messages_21.png]({{site.baseurl}}/images/Guest_Messages_21.png)


 
 Finally, if you check on the _Profile Documents_, the template will show in the _Profiles_ area:  
 

![guest_messages_22.png]({{site.baseurl}}/images/guest_messages_22.png)



 
 - When finished, click on the button _Save_ at the bottom of the screen.
 


{{site.data.alerts.note}} If your property has any inclusive tax or fee that you want to show on your Invoice tax, please contact our team at help@frontdeskanywhere.com: our team will be able to change the template for you! {{site.data.alerts.end}}




## Automated Emails  
 
Once your _Email Templates_ are set up, you can configure the system to automatically send those templates to your guests at key points during their reservation process and stay.  

 - In the Admin Settings, click on the link **Automated Emails** under section _General_:  
 
![messages_23.png]({{site.baseurl}}/images/messages_23.png)



 
 - The first column _Folio Status Action_ identifies what change of  reservation status will trigger the automatic email.


![Guest_Messages_24.png]({{site.baseurl}}/images/Guest_Messages_24.png)


Note that the status _Automatically Send Email Upon Folio Creation_ only interests those folios manually created on your Tape Chart. If you want to have the system send an automatic email when your guests book online, you will need to active the _Automatically Send IBE Confirmation Email_.  

 
 - Under column _Automated E-mail Status_ check the box corresponding to the action you want the system to perform. In the example below I am choosing to have the system to send an automatic email any time a reservation is created on the Tape Chart:  
 
 
![Guest_Messages_25.png]({{site.baseurl}}/images/Guest_Messages_25.png)


 

 - Select what email template you want to use by choosing one from the available options in the scroll down menu: 


![Guest_Messages_26.png]({{site.baseurl}}/images/Guest_Messages_26.png)

 
- Finally, enter the email address you want to send a copy of the email to:  

![Guest_Messages_34.png]({{site.baseurl}}/images/Guest_Messages_34.png)



 - When finished, click on the blue button _Save_ at the bottom of the page:  
 
![Guest_Messages_27.png]({{site.baseurl}}/images/Guest_Messages_27.png)


 

## Email Rules 

_Email rules_ is the tool that enables you to send automatic emails outside the sphere of any folio activity (reservation confirmation, check-in, check-out, and cancellation). Differently from the _Automated Emails_ where those emails are triggered by some change in the status of a reservation folio, _Email Rules_ do not have any constrain in terms of the time at which the email is sent: you simply set the condition yourself! This comes useful when you want to send a remainder to your guests for their upcoming arrival or at times when you want to send a "thank you" message to your guests after their stay.  


{{site.data.alerts.important}} You will have to have both Email Templates enabled and Guest Messages set up before placing Email Rules. {{site.data.alerts.end}} 

 - In the Admin Settings, click on the link **Email Rules** under section _General_:  
 

![messages_28.png]({{site.baseurl}}/images/messages_28.png)


 
 - Start by clicking on the blue button _Add_:  
 
 
![Guest_Messages_29.png]({{site.baseurl}}/images/Guest_Messages_29.png)



 
 - You will be promopted to fill in some fields:  
 
 ![Guest_Messages_30.png]({{site.baseurl}}/images/Guest_Messages_30.png)

 
  
 **Title**: the _Title_ field will appear as the email subject of the message.  
 **Status**: the _Status_ checkbox controls whether the email rule is active or not.  
 **CC Email Addresses**: you can insert this field if you want to have a copy of each message that gets sent. Note that you can enter multiple addresses, just make sure to have them separated by one coma.  
 **Trigger**: this is how you decide when to send the message. You will see three drop down menus, you will simply need to make your selection.  
 **Messages**: this is where you decide which message you want to include in the email: the list of messages  will reflect the templates that you have currently active.  
 **Room Type & Rates**: emails to be sent are individuated on a rate level: for each room type, select the rate/s you want the rule to include. For example, if you check the box _King_, the email will be sent only to those folios to which this particular rate is assigned. 






 - When finished, click on the blue button _Save_ at the bottom of the page.
