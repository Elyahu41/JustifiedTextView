# JustifiedTextView
Use this file to Justify text in your TextView in your android apps.

I made sure that this works for Left-to-Right languages and RTL langauges. Since no other text justification code worked properly, ans as of now, Android is also having an issue justifying text with RTL languages (besides for Pixel devices).

Just copy the file into your project and you should be able to use it right away as a regular textview programmatically or in XML.

## WARNING
Gravity might affect the text justification. For my needs, I just made sure that the text justification did not occur when the gravity was equal to CENTER. But you may need to change that based on your use case.
