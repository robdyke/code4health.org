---
permalink: "/training-improvement/"
layout: page
title:  "Training Improvement"
---

<section class="bg-primary text-white" id="about" style="padding-bottom:50px">
      <div class="container text-center">
        <h2 class="mb-4">Mental Health Chatbot & NLP Enabled Triage</h2>
       </div>
       <hr class="light my-4">
</section>

<section id="chat-bot" style="padding-top:50px">
      <div class="container">
        <div class="row">
          <div class="col-lg-12">
<p><b><span style="background-color: initial;">Aims<br>
</span></b>Working with Code4Health and first year students from UCL Department of Computer Science, we aim to produce a measurable improvement in the standard of Trauma &amp; Orthopaedic (T&amp;O) training by gathering feedback by text from the trainees, then supplying weekly collated group feedback to those hospitals training them.</p>

<p>We aim to pilot this in T&amp;O within the Northern Deanery. The impact of the feedback would be assessed scientifically in a randomised trial between hospitals, after gaining consent from trainees.<br>
 The expectation would be this software would eventually be used by other healthcare specialties including all those supported by Health Education England (160,000 students).</p>

<p>Outline of proposed method</p>

<ul>
<ul>
	<li>Include a specific group of trainees (e.g for the pilot, only trainees with a National Training Number (ST3 upwards) in the Health Education North East T&amp;O)</li>
</ul>
</ul>
<ul>
<ul>
	<li>Weekly texts sent to trainees at end of working week</li>
</ul>
</ul>
<ul>
<ul>
	<li>Anonymous pooling of the response data</li>
</ul>
</ul>
<ul>
<ul>
	<li>Questions regarding training could be multiple and should be configurable but the default would be “Please rate your training this week 0-10, or * for “cannot comment” or # to “change details””. This question and the responses should be configurable in the database.</li>
</ul>
</ul>
<ul>
<ul>
	<li>Weekly feedback from trainees to be provided back to trainers at a trust level (to help maintain anonymity of trainees)</li>
</ul>
</ul>
<ul>
<ul>
	<li>The impact of this intervention would be measured scientifically. Trusts to be randomised as “cross-over trial”- 3/6 months on each arm (i.e. consultants receiving their feedback vs not). Exact details to be confirmed having sought statistician’s advice.</li>
</ul>
</ul><b>Functionality requirements:</b><b><br>
</b><b style="background-color: initial;"><i>Administrators pages (via a login)</i></b>
<p>The database will require administration to allow the project to be initiated and maintained.<br>
 This administrator would set the group from a pick list (https://hee.nhs.uk/hee-your-area). They would pick from a specialty list that we will supply; T&amp;O for the pilot.<br>
 The administrator would then invite the identified group of trainees to register - and they would have the ability to add new trainees and remove old ones as time progresses. This would be in the form of a webpage link they are sent.<br>
<span style="background-color: initial;">The administration pages will have a section to add/change the trainee list, and the day/time&nbsp;</span><span style="background-color: initial;">for the texts to go out (normally 17:01hrs every Friday).<br>
</span>The administration pages will have an engagement page with the following information, “In&nbsp;<span style="background-color: initial;">the last 4 weeks the following trainees have left feedback about the following hospitals:…”.<br>
</span>This will stop people giving feedback about other places that they are not currently working&nbsp;<span style="background-color: initial;">in. No raw data such as individual scores can be seen by the administration team, or the data&nbsp;</span><span style="background-color: initial;">analysis team.<br>
</span>The administration pages require a download page where the raw data is collated but this&nbsp;<span style="background-color: initial;">should not show the individual details of the trainee who gave the feedback. It should&nbsp;</span><span style="background-color: initial;">contain:</span></p>

<ul>
<ul>
	<li>Date/time of feedback request</li>
</ul>
</ul>
<ul>
<ul>
	<li>Date/time of feedback received (only count for analysis within 48 hours)</li>
</ul>
</ul>
<ul>
<ul>
	<li>Current trust</li>
</ul>
</ul>
<ul>
<ul>
	<li>Trust feedback of collated data (Y/N)</li>
</ul>
</ul>
<ul>
<ul>
	<li>Score 1-10 or * or #.</li>
</ul>
</ul>The admin pages will have a section to add/change the feedback list. This is the email&nbsp;<span style="background-color: initial;">addresses to receive the feedback (e.g. the T&amp;O trainers and trainees in the North East), and&nbsp;</span><span style="background-color: initial;">the day/time for this feedback to go out (normally 07:59hrs every Monday).</span>
<b style="background-color: initial;"><i>Trainees pages (no login but via a unique link)</i></b>

<p>Trainees would need to consent to the data above being collected and stored and to being&nbsp;<span style="background-color: initial;">involved in the study. There would be information to trainees regarding a clear explanation of&nbsp;</span><span style="background-color: initial;">mode of security of data, exactly what is done with the data, how it is kept anonymous, and&nbsp;</span><span style="background-color: initial;">how it is going to be fed back to the trainers. It would explain that trainees have the ability to&nbsp;</span><span style="background-color: initial;">exit the study whenever they wish. This section would read like a terms and conditions page.</span></p>

<p>The trainees would then enter their details:</p>

<ul>
<ul>
	<li>Name</li>
</ul>
</ul>
<ul>
<ul>
	<li>Current hospital trust</li>
</ul>
</ul>
<ul>
<ul>
	<li>Mobile phone number</li>
</ul>
</ul><b><i>Text messages</i></b>
<p>Weekly texts to trainees need to be generated, sent out, and the responses (via text&nbsp;<span style="background-color: initial;">message) need to be collated.<br>
</span>A text would look like this. “We currently have you listed as training at XX hospital: Please&nbsp;<span style="background-color: initial;">rate your training this week 0-10, or * for “cannot comment”, or # to “update details”. This&nbsp;</span><span style="background-color: initial;">question and the responses should be configurable in the database. The “update details”&nbsp;</span><span style="background-color: initial;">option should send a web link back to them allowing a trainee to update their name, hospital&nbsp;</span><span style="background-color: initial;">or phone number, or to withdraw from the study.<br>
</span>A further ‘reminder notification’ at 24 hours if no response received (time/number of&nbsp;<span style="background-color: initial;">reminders modifiable). A maximum of 1 response per trainee per week to be included in&nbsp;</span><span style="background-color: initial;">analysis.</span></p>

<p><b style="background-color: initial;"><i>Weekly feedback to trainers</i></b><span style="background-color: initial;"><br>
</span></p>

<p>Mean scores for the hospital will be sent out in a league table to predefined email addresses&nbsp;<span style="background-color: initial;">(the feedback list). This will be accompanied by some explanatory text. It will include mean&nbsp;</span><span style="background-color: initial;">scores for all Trusts that are randomised for feedback and have therefore received feedback&nbsp;</span><span style="background-color: initial;">that week.<br>
</span>To determine if this software leads to an improvement in training, we will randomise the&nbsp;<span style="background-color: initial;">trusts to receive weekly feedback, or not. Administration pages will need to ensure output of&nbsp;</span><span style="background-color: initial;">data runs alongside the randomisation schedule and ensure trusts receive feedback only at&nbsp;</span><span style="background-color: initial;">the correct time. At any specific time point a trust may be randomised to either receive&nbsp;</span><span style="background-color: initial;">feedback or not, and that allocation may change (a cross over trial).</span></p>

<center><img src="/assets/img/workflow.jpg"></center>

        
      </div>
	  </div>
	  </div>
    </section>
