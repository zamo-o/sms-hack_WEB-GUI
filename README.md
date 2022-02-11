# SMS *'hack'* with web GUI


  Simple website which function is to send SMS message to your desired destination. 
  
  It is based on [Textbelt](https://textbelt.com/), they handle the SMS sending. Have to mention, as it is free, there is limitation of 1 SMS per day. 
 > (per IP, so using VPN and constantly changing location after every sent SMS will work). It does not count 24H from your request, but resets on 00:00 (midnight)
  
  After clicking the button, JavaScript sends POST request to https://textbelt.com/text with body content (see in the code). The "key" is set to 'textbelt' which means using it for free with the limitation, however you can buy some SMSs and replace the 'textbelt' with your generated textbelt key.
  
  ## Sending
  First, type the destination telephone number  _**with prefix**_ all together, no spaces.
  Then type your message, maximum length is 150 characters. Also sending special characters like č, ř, á, and so will return false.

