---
layout: post
title: Preauthorisation approval - a necessary step?
description: what is preauthorisation approval and why is it necessary? 
keywords: preauthorisation,  approval, ICD10, service, procedure code, ICD10 code, category of services, claim denied, partial approval, claim approval, claim, filing, health insurance, remittance, electronic remittance, initial review, payer, provider, payment, claim review
---

<p style="text-align: justify;line-height: 1.7">
Preauthorisation approval is a process where the patient through provider seeks a prior approval from the payer for receiving certain types of care, medication or treatment from the provider. If the preauthorisation approval is not requested before receiving specific categories of procedures then payer may refuse to pay for those procedures or medications thus increasing burden on patient to pay for treatment. There is also a danger of increased bad debt for providers, in case the patient is unable to pay for the treatment for which preauthorisation approval was not requested. </p> <br />

<p style="text-align: justify;line-height: 1.7">
Through preauthorisation, the payer determines and validates the medical necessity and aptness of the procedure prescribed by the provider. Preauthorisation approval helps payer keep a tab on healthcare costs by preventing duplicate and unnecessary services, while offering patients generic alternatives, if available. Preauthorisation is also leveraged by providers to cover the risk of non-payment when patient insists on payer coverage. 
</p> <br />

<p style="text-align: justify;line-height: 1.7">
Preauthorisation can be mandated by the payer for any of the following:
1. Admission to hospital - emergency or non-emergency inpatient
2. Referral to a specialist
3. Performing specific categories of service
4. Prescribing specific categories of medicines even when generics are available
</p> <br />

<p style="text-align: justify;line-height: 1.7">
Imagine visiting a Dentist, who is within payer’s network, for half-yearly dental checkup. Most dental insurance policies offer two cleanings in a year. During such visit, the dentist examines and detects deep cavities on molars, which requires root canal treatment (RCT) and crowns. Per the dental insurance policy, preauthorisation from payer is required before provider performs RCT and cements crown. The provider contacts the payer to confirm the need of the preauthorisation. If preauthorisation is required then provider with the help of coder sends the preauthorisation request along with necessary patient health information to payer in X12 278 file format version 5010. The payer sends a response acknowledging receiving the preauthorisation form in X12 278 file format. The payer or third-party administrator (TPA) then reviews the preauthorisation request form and contacts the provider or patient in case more information such as X-Rays, charts, notes etc. is required. After the decision has been made, the payer communicates the decision to the provider in X12 278 file format. Until the decision is made, the provider is free to reach out to payer to know the status of preauthorisation. The payer responds with ‘pending’ or ‘need more review’ response until the final decision is made on the request. 
</p> <br />

<p style="text-align: justify;line-height: 1.7">
Following are the key information required while requesting preauthorisation approval:
1. Patient Details
2. Ordering Physician Details
3. Rendering Patient Details
4. Type of Service
5. Type of Procedure
6. Type of Device(s) being used
7. Additional details on procedure
8. Whether the request in emergency, non-emergency or elective
9. ICD-10 code of the primary procedure
10. Planned date of the procedure
11. Site where the procedure/service will be provided (Office, Outpatient Hospital, Ambulance, Home, Inpatient etc.)
</p> <br />

<p style="text-align: justify;line-height: 1.7">
If there are more procedures or services for which preauthorisation approval is requested then information from 4 (Type of Service) to 11 (Site of Service) are repeated for each service or procedure.
</p> <br />

<p style="text-align: justify;line-height: 1.7">
The outcome of the preauthorisation are any of the following:
1. approved in full, i.e. all prescribed services can be provided to the patient
2. approved in part, i.e. only a few among all prescribed services can be provided to patient per policy. The reason for denial of other prescribed services is also provided by the payer in the response
3. denied, i.e. no authorisation is provided for the prescribed services. If patient and provider still go ahead with the prescribed services then payer will not be covering or remitting or reimbursing any monies for those services
</p> <br />

<p style="text-align: justify;line-height: 1.7">
With the denial, the payer can insist the patient go through an intermediate ‘fail first’ process, wherein a provider and patient must first see unsuccessful results from a generic or alternative, yet cheaper, service preferred by the payer. Only after the ‘fail first’ treatment or service has failed, the payer will provide the preauthorisation approval.  
</p> <br />

<p style="text-align: justify;line-height: 1.7">
Preauthorisation approval has been deemed as extremely burdensome by 387 of the 400 providers that **kclstr** reached out to. Typically a provider and his/her staff spend over 1.8 hours a day in preauthorisation process, a valuable time which should be spent on treating patients otherwise.  On an average it takes 5-7 days to receive preauthorisation approval, and until then patients and providers are held back on treatments and follow-ups fearing mounting healthcare costs. An instant preauthorisation approval system will ensure that no patient has to wait more than a few seconds to seek any treatment that is necessary for patient’s wellbeing. It is also important to simplify and standardise the preauthorisation across payers so that time to complete the preauthorisation process can be less than two minutes.
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
