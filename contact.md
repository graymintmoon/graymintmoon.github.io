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
		</fieldset>
		<fieldset class="form_fieldset">
			<h3 class="form_section_title text_center">About Your Company</h3>
			<label class="form_label" for="company-name">Your company name<span class="text_red">*</span></label>
			<input class="form_input" type="text" name="company-name" required>
			<div class="form_two_columns">
				<div class="form_column">
					<label class="form_label" for="company-email">Your company email</label>
					<input class="form_input" type="email" name="company-email">
				</div>
				<div class="form_column">
					<label class="form_label" for="company-phone">Your company phone number</label>
					<input class="form_input" type="tel" name="company-phone">
				</div>
			</div>
			<label class="form_label" for="company-address">Your company address</label>
			<input class="form_input" type="text" name="company-address">
		</fieldset>
		<fieldset class="form_fieldset">
			<h3 class="form_section_title text_center">Let's discuss your website</h3>
			<div class="form_two_columns">
				<div class="form_column">
					<label class="form_label" for="company-url">Your URL address (if available)</label>
					<input class="form_input" type="text" name="company-url">
				</div>
				<div class="form_column">
					<span class="form_label">Do you own this domain?</span>
					<div class="form_inline_inputs">
						<div class="form_inline_input_item">
							<input class="form_checkbox" type="checkbox" id="company-owned-url" name="company-owned-url" value="yes">
							<label class="form_checkbox_label" for="company-owned-url">Yes</label>
						</div>
						<div class="form_inline_input_item">
							<input class="form_checkbox" type="checkbox" id="company-owned-url" name="company-owned-url" value="not yet">
							<label class="form_checkbox_label" for="company-owned-url">Not yet</label>
						</div>
					</div>
				</div>
			</div>
			
			<span class="form_label" for="company-phone">Do you need us to buy your domain?</span>
			<div class="form_inline_inputs">
				<div class="form_inline_input_item">
					<input class="form_checkbox" type="checkbox" id="buy-domain" name="buy-domain" value="yes">
					<label class="form_checkbox_label" for="buy-domain">Yes please</label>
				</div>
				<div class="form_inline_input_item">
					<input class="form_checkbox" type="checkbox" id="buy-domain" name="dont-buy-domain" value="no thanks">
					<label class="form_checkbox_label" for="dont-buy-domain">No thanks</label>
				</div>
			</div>
		</fieldset>
		<fieldset class="form_fieldset">
			<h3 class="form_section_title text_center">Some helpful information</h3>
			<label class="form_label" for="budget">What is your estimated budget?</label>
			<input type="text" class="form_input" name="budget">

			<label class="form_label" for="ideal-date">When is your ideal due date?</label>
			<input class="form_input" id="idealDate" type="date" name="ideal-date">

			<label class="form_label" for="website-reason">What are your main reasons for wanting to build a website?<span class="text_red">*</span></label>
			<textarea class="form_textarea" rows="3" type="text" name="website-reason" required></textarea>

			<label class="form_label" for="target-audience">Describe your target audience or potential clients:<span class="text_red">*</span></label>
			<textarea class="form_textarea" rows="3" type="text" name="target-audience" required></textarea>

			<label class="form_label" for="products-services">What unique products or services do you offer your audience/clients?<span class="text_red">*</span></label>
			<textarea class="form_textarea" rows="3" type="text" name="products-services" required></textarea>

			<label class="form_label" for="favorite-sites">What are 3 of your favorite websites and why?<span class="text_red">*</span></label>
			<textarea class="form_textarea" rows="3" type="text" name="favorite-sites" required></textarea>
			
			<label class="form_label" for="3 words">List 3 key words that describe your company:</label>
			<input type="text" class="form_input" name="3 words">

			<label class="form_label" for="competitors">Who are your top 3 competitors:</label>
			<input type="text" class="form_input" name="competitors">

			<label class="form_label" for="reference">How did you hear about us?</label>
			<input class="form_input" name="reference" type="text">

			<label class="form_label" for="extra-info">Is there anything else you would like to tell us?</label>
			<textarea class="form_textarea" name="extra-info" rows="3"></textarea>
		</fieldset>
		<input class="form_submit text_charcoal" type="submit" value="Submit">
	</form>
</div>