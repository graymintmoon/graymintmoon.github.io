---
layout: page
title: Contact
---
<div class="form_block">
	<div class="form_introduction text_center">
		<div class="container_lg">
			<h2 class="text_charcoal">Hello!</h2>
			<h4>Thank you for your interest in working with us. We are excited to learn more about you, your business, and your overall goals. Or, you can email us at <a class="text_jungle text_regular" href="mailto:graymintmoon">graymintmoon@gmail.com</a> to get the conversation going!</h4>
		</div>
	</div>
	<form action="https://formspree.io/graymintmoon@gmail.com"
		method="POST">
		<input class="contact-form" type="hidden" name="_next" value="/">
		<fieldset class="form_fieldset">
			<h3 class="form_section_title text_center">About You</h3>
			<label class="form_label" for="name">Your name</label>
			<input class="form_input" type="text" name="name">
			<div class="form_two_columns">
				<div class="form_column">
					<label class="form_label" for="email">Your email</label>
					<input class="form_input" type="email" name="email">
				</div>
				<div class="form_column">
					<label class="form_label" for="phone">Your phone number</label>
					<input class="form_input" type="tel" name="phone">
				</div>
			</div>
		</fieldset>
		<fieldset class="form_fieldset">
			<h3 class="form_section_title text_center">About Your Company</h3>
			<label class="form_label" for="company-name">Your company name</label>
			<input class="form_input" type="text" name="company-name">
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
			<label class="form_label" for="ideal-date">Do you have an ideal due date?</label>
			<input class="form_input" id="idealDate" type="date" name="ideal-date">
			<label class="form_label" for="website-reason">What are your main reasons for wanting to build a website?</label>
			<textarea class="form_textarea" rows="3" type="text" name="website-reason"></textarea>
			<label class="form_label" for="target-audience">Describe your target audience or potential clients:</label>
			<textarea class="form_textarea" rows="3" type="text" name="target-audience"></textarea>
			<label class="form_label" for="products-services">What unique products or services do you offer your audience/clients?</label>
			<textarea class="form_textarea" rows="3" type="text" name="products-services"></textarea>
			<label class="form_label" for="extra-info">Is there anything else you would like to tell us?</label>
			<textarea class="form_textarea" name="extra-info" rows="3"></textarea>
		</fieldset>
		<input class="form_submit" type="submit" value="Submit">
	</form>
</div>