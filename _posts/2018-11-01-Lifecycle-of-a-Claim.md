---
layout: post
title: Lifecycle of a Claim
description: what happens from the moment claim is filed until the doctor gets the money?
keywords: EDI, adjudication, claim, filing, 277CA, X12 834, X12 835, electronic remittance, claim authentication, payer, provider
---

<p style="text-align: justify;line-height: 1.7">
Insurance is a critical pillar in the healthcare journey of a patient. Any patient who has gone to a hospital or clinic for receiving any treatment values the need of having insurance.  A lot of backend work is undertaken by the doctor or his/her staff and other healthcare providers while dealing with insurance.  
</p> <br />

<p style="text-align: justify;line-height: 1.7">
Healthcare providers get paid when they submit claim to the patient’s insurance provider, who are commonly called as Payers. Claim is a detailed and itemised statement of services provided and procedures carried by the provider while treating the patient. The payer or a partner vendor service provider for payer validates, verifies and adjudicates the claim. A successful adjudication of claim results in Electronics Remittance Advice File and money being remitted to provider. A denial by payer leads to additional paperwork for providers and patients. 
</p> <br />

<p style="text-align: justify;line-height: 1.7">
Imagine visiting a Dentist, who is within the payer’s network, for a dental checkup. Imagine dentist taking a few X-Rays, deep-cleaning teeth, and filling a few cavities. The dentist has performed a number of procedures here: X-Rays, cleaning and filling. To get paid for these services, the dentist files a claim with the patient’s payer. The claim, at its basic level, will contain information of patient, provider, payer, and all procedures carried out by provider along with any pre-authorisation approvals for specific category of procedures. The claim has to be converted into a format that payer can understand. This process of converting claim into a format that payer can understand is called Coding. The coding is either done by the providers, their patient management systems or through third-party vendors called clearinghouse. At this stage, the Provider or the Coder categorises the procedures according to [ICD-10](http://apps.who.int/classifications/icd10/browse/2016/en) rules. The provider’s notes, care summary and ICD codes are then sent to the payer. The claims can be sent electronically, faxed or mailed via snail mail. Over 70% of claims are filed electronically, and there is a greater push by payers and the government for electronic claims. 
</p> <br />

<p style="text-align: justify;line-height: 1.7">
The data exchange with Payer happens in EDI X12 format at all times. Claims are electronically submitted by the Provider/Coder in an X12 837 file format. After receiving the claim the payer sends a 277CA file, which is an acknowledgment of having received the claim in X12 837 file. The 277 CA acknowledgment informs the provider or coder whether the claim file had all the information needed for acceptance and adjudication. If not, the 277CA acknowledgment sends an instruction to make changes to the claim and re-submit. After the claim has been accepted by the payer, adjudication process begin. Adjudication is the step where decision gets made on whether to pay the provider, and if so then how much to pay the provider and how much to bill the patient.
</p> <br />

<p style="text-align: justify;line-height: 1.7">
Adjudication typically takes 5 days to a few weeks. During this time, the provider/coder initiates contact with payer through X12 276 request to know the status of the claim. For every such request made by the provider or coder, the payer sends X12 277 response listing the status of the claim. Post adjudication by the payer, the provider receives the X12 835 file containing whether the claim was denied or approved, and if approved, information on how much is paid to provider, how much billed to the patient, and the remittance details to the provider. This X12 835 file is called as Electronic Remittance Advice File. If the claim is denied for any reason then X12 835 contains detailed reasons for denial.
</p> <br />

<p style="text-align: justify;line-height: 1.7">
In addition, the patient also receives an X12 835 5010 file called as Explanation of Benefits (EOB) that contains protected health information of patient along with information on payer, benefits, amount claimed by and paid to provider, and amount billed to patient, if any. 
</p> <br />

<p style="text-align: justify;line-height: 1.7">
Once the provider and patient have received their X12 835 files, the claim is closed. There are a lot of inefficiencies in the way claims are currently managed. Lifecycle of claim, i.e. from submission to remittance and payment, can easily run for weeks.
</p> <br />


<form action="https://gmail.us20.list-manage.com/subscribe/post?u=0e628327d496d7cbe86598540&amp;id=801bf936e2" method="post" id="mc-embedded-subscribe-form" name="mc-embedded-subscribe-form" class="validate" target="_blank" novalidate>
    <div id="mc_embed_signup_scroll">
	<h2>Subscribe to our mailing list</h2>
<div class="mc-field-group">
	<label for="mce-EMAIL">Email  <span class="asterisk">*</span>
</label>
	<input type="email" value="" name="EMAIL" class="required email" id="mce-EMAIL">
</div>
<div class="mc-field-group">
	<label for="mce-FNAME">Name  <span class="asterisk">*</span>
</label>
	<input type="text" value="" name="FNAME" class="required" id="mce-FNAME">
</div>
	<div id="mce-responses" class="clear">
		<div class="response" id="mce-error-response" style="display:none"></div>
		<div class="response" id="mce-success-response" style="display:none"></div>
	</div>    
    <div style="position: absolute; left: -5000px;" aria-hidden="true"><input type="text" name="b_0e628327d496d7cbe86598540_801bf936e2" tabindex="-1" value=""></div>
    <div class="clear"><input type="submit" value="Subscribe" name="subscribe" id="mc-embedded-subscribe" class="button"></div>
    </div>
</form>

<script type='text/javascript' src='//s3.amazonaws.com/downloads.mailchimp.com/js/mc-validate.js'></script><script type='text/javascript'>(function($) {window.fnames = new Array(); window.ftypes = new Array();fnames[0]='EMAIL';ftypes[0]='email';fnames[1]='FNAME';ftypes[1]='text';fnames[3]='ADDRESS';ftypes[3]='address';fnames[4]='PHONE';ftypes[4]='phone';fnames[5]='BIRTHDAY';ftypes[5]='birthday';}(jQuery));var $mcj = jQuery.noConflict(true);</script>

<br /> 
