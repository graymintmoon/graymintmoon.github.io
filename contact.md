---
layout: page
title: Contact
description: The Gray Mint Moon Contact Form. Potential clients or businesses who are interested in having us work on your website can fill in our contact form.
---
<div class="form_block">
	<div class="form_introduction text_center">
		<div class="container_lg">
			<h1 class="page_title">Contact<br><span class="page_title_second">Us</span></h1>
			<h4 class="page_subtitle">We'd love to hear from you!</h4>
			<hr class="divider_red">
			<p>Thank you for your interest in working with us. Please fill out and submit the questionnaire so that we can learn more about who you are and how we can help.</p>
		</div>
	</div>
	<form action="https://formspree.io/graymintmoon@gmail.com"
		method="POST">
		<input class="contact-form" type="hidden" name="_next" value="/success">
		<fieldset class="form_fieldset">
			<h3 class="form_section_title text_center">About You</h3>
			<label class="form_label" for="name">Your name<span class="text_red">*</span></label>
			<input class="form_input" type="text" name="name" required>
			<div class="form_two_columns">
				<div class="form_column">
					<label class="form_label" for="email">Your email<span class="text_red">*</span></label>
					<input class="form_input" type="email" name="email" required>
				</div>
				<div class="form_column">
					<label class="form_label" for="phone">Your phone number</label>
					<input class="form_input" type="tel" name="phone">
				</div>
			</div>
			<label class="form_label" for="company-name">Your business/brand name<span class="text_red">*</span></label>
			<input class="form_input" type="text" name="company-name" required>
			<label class="form_label" for="company-url">Your URL address (if available)</label>
			<input class="form_input" type="text" name="company-url">
			
		</fieldset>
			
		
		<fieldset class="form_fieldset">
			<h3 class="form_section_title text_center">Some helpful information</h3>
			<label class="form_label" for="budget">What is your estimated budget?<span class="text_red">*</span></label>
			<input type="text" class="form_input" name="budget" required>

			<label class="form_label" for="website-reason">What are your main reasons for wanting to build a website?<span class="text_red">*</span></label>
			<textarea class="form_textarea" rows="3" type="text" name="website-reason" required></textarea>

			<label class="form_label" for="reference">How did you hear about us?</label>
			<input class="form_input" name="reference" type="text">

			<label class="form_label" for="extra-info">Is there anything else you would like to tell us?</label>
			<textarea class="form_textarea" name="extra-info" rows="3"></textarea>
		</fieldset>
		<input class="form_submit text_charcoal" type="submit" value="Submit">
	</form>
</div>