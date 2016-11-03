# Responive Email Template
A responsive email template that is supported in the majority of email clients. It is responsive for web down to mobile devices.

###Technical Details:
* Due to email limitations the html must use inline styling and no javascript. As a result it is built of almost entirely tables.
* Has a background image which it accounts for Outlook specifically with VML hack.
```HTML
<td background="images/header-bg.jpg" bgcolor="#404040" width="640" valign="top" class="100p">
  <!--[if gte mso 9]>
    <v:rect xmlns:v="urn:schemas-microsoft-com:vml" fill="true" stroke="false" style="width:640px;">
    <v:fill type="tile" src="images/header-bg.jpg" color="#404040" />
    <v:textbox style="mso-fit-shape-to-text:true" inset="0,0,0,0">
  <![endif]-->
```

####[Template Preview][preview]
[preview]: ./images/preview.png
