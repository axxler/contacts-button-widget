# contacts-button-widget
Website contacts widget: button &amp; contacts form: start chat in whatsapp, telegram, viber, callback etc. HTML, CSS  &amp; a bit of jQuery. 
3 minutes to intall. 100% free to use.

## Install
Just add js & css project links and copy html code into the bottom of your <body> section. Change phone +199999999999 to your actual number, facebook account, /contact-us to actual contact page link

## Required
[jQuery](https://jquery.com/), [Font Awesome](https://github.com/FortAwesome/Font-Awesome)

## Compatibility
Font Awesome 4.X.X or 5.X.X

### Examples:
- Contacts button widget for FontAwesome4
- Contacts button widget for FontAwesome4 - 1 html page with built-in JS & CSS [(link)](https://github.com/axxler/contacts-button-widget/blob/main/examples/contacts-button-widget_fa_4_7_0_one_page_css_js.html)
- Contacts button widget for FontAwesome5
- Contacts button widget for FontAwesome5 - 1 html page with built-in JS & CSS [(link)](https://github.com/axxler/contacts-button-widget/blob/main/examples/contacts-button-widget_fa_5_9_0_one_page_css_js.html)

## PREVIEW
CSS #contact_widget_button style right bottom by default

![contacts-button-widget preview](/preview/1.gif)

### Source
```
  <body>
  <-- ... -->
  <-- AFTER MAIN PAGE CONTENT -->
	<h1 class="center">Contacts button widget</h1>
	<!-- [START] Contact Widget Button -->
	<div id="contact_widget_substrate"></div>
	<div id="contact_widget_button" class="contact_widget_left d-flex align-items-center justify-content-center">
		<div class="contact-widget-pulsation"></div>
		<div class="contact-widget-icon text-center d-flex align-items-center justify-content-center"><i class="fa fas fa-envelope"></i><span class="contact-widget-text d-none">Contact button</span></div>
		<div class="contact-widget-dropdown d-flex flex-column align-items-start">
			<a rel="noopener noreferrer" href="https://m.me/my-facebook-messenger" target="_blank" class="contact-widget-item d-flex align-items-center"><span class="contact-widget-item-icon contact-widget-messenger d-flex align-items-center justify-content-center"><i class="fab fa-facebook-messenger"></i></span><span>Messenger</span></a>		
			<a rel="noopener noreferrer" href="https://api.whatsapp.com/send?phone=+199999999999" target="_blank" class="contact-widget-item d-flex align-items-center"><span class="contact-widget-item-icon contact-widget-whatsapp d-flex align-items-center justify-content-center"><i class="fab fa-whatsapp"></i></span><span>WhatsApp</span></a>
			<a rel="noopener noreferrer" href="https://t.me/+199999999999" target="_blank" class="contact-widget-item d-flex align-items-center"><span class="contact-widget-item-icon contact-widget-telegram d-flex align-items-center justify-content-center"><i class="fab fa-telegram"></i></span><span>Telegram</span></a>
			<a rel="noopener noreferrer" href="viber://chat?number=+199999999999" target="_blank" class="contact-widget-item d-flex align-items-center contact-widget-viber-desktop"><span class="contact-widget-item-icon contact-widget-viber d-flex align-items-center justify-content-center"><i class="fa-phone-square fab fa-viber"></i></span><span>Viber</span></a>
			<a rel="noopener noreferrer" href="viber://add?number=+199999999999" target="_blank" class="contact-widget-item d-flex align-items-center contact-widget-viber-mobile"><span class="contact-widget-item-icon contact-widget-viber d-flex align-items-center justify-content-center"><i class="fa-phone-square fab fa-viber"></i></span><span>Viber</span></a>
			<a rel="noopener noreferrer" href="mailto:email@to.me" class="contact-widget-item d-flex align-items-center"><span class="contact-widget-item-icon contact-widget-email d-flex align-items-center justify-content-center"><i class="far fa-envelope fa fa-envelope-open"></i></span><span>email@to.me</span></a>
			<div href="javascript:;" data-src="#callback_form" data-fancybox class="contact-widget-item d-flex align-items-center">
				<span class="contact-widget-item-icon contact-widget-call d-flex align-items-center justify-content-center"><i class="fas fa fa-phone"></i></span><span>Callback request</span>
			</div>
			<a href="/contact-us" class="contact-widget-item d-flex align-items-center"><span class="contact-widget-item-icon contact-widget-contacts d-flex align-items-center justify-content-center"><i class="fas fa fa-address-book"></i></span><span>Our contacts</span></a>
		</div>
	</div>
	<!-- [END] Contact Widget Button -->

<link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.9.0/css/all.min.css" rel="stylesheet" media="screen" />
<link href="../css/contacts-button-widget.css" rel="stylesheet" media="screen" />
<script src="https://cdnjs.cloudflare.com/ajax/libs/jquery/3.6.0/jquery.min.js"></script>
<script src="../js/contacts-button-widget.js></script>
</body>
```
