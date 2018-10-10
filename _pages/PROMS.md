---
permalink: "/PROMs/"
layout: page
title:  "Patient Reported Outcome Measures - open-PROMs
---

<section class="bg-primary text-white" id="about" style="padding-bottom:50px">
      <div class="container text-center">
        <h2 class="mb-4">Patient Reported Outcome Measures - open-PROMs</h2>
       </div>
       <hr class="light my-4">
</section>

<section id="PROMs" style="padding-top:50px">
    <div class="container">
      <div class="row">
        <div class="col-lg-12">
              <p>Operations on patients always have an impact, hopefully for the better, sometimes for the worse. There is variability in outcomes, which can depend on patient factors but can also depend upon the surgical teams that perform the surgery. So that any variability in outcomes in patient groups can be studied and improvements in care made, ‘Outcome Measures’ are collected. These are often patient completed questionnaires to formally score patients pain and function before and after surgery. Patient Reported Outcome Measures are known as PROMs.</p>
              <p>Some trusts now routinely collect questionnaires to compare patients’ pre-operative and post-operative scores to inform clinical practice and drive improvement. The questionnaires are normally specific to the operation that has been performed (e.g. knee replacement scores, or hernia scores) and most operations will also have a more general health status score applied as well (known as EQ-5D). EQ-5D can be applied across all aspects of healthcare and is a good way to work out how much impact an operation may have on health compared to say treatment for diabetes. This helps healthcare providers direct money to the interventions that have the most patient benefit.</p>
              <p>Trusts currently collect the data in paper format which is then converted into an electronic format for storage and analysis purposes (usually via manual input). There are commercial options available but these routinely cost each NHS trust around £50,000 PA and given the financial crisis in the NHS these budgets are being cut.</p>
              <p>The aim of this open source project is to make the software (which would sit within NHS servers for governance purposes) available so any healthcare organisation could use it without the costs associated with a software licence. Investment can be redirected to continuous development of the software (with clinical input) plus training and support. The first module has already been written with the support of NHS Digital, the Code4Health initiative and its partners.</p>
              <p>All data collected via the software will be held in an open format (openEHR) to facilitate future interoperability with other hospital systems.</p>
              <p>Ultimately, we need a database with a clean-looking, user-friendly interface into which we can enter thousands of patients’ worth of data including:</p>
              <ul>
                <li>patient demographics (name, D.O.B, NHS number (unique to the patient)</li>
                <li>Hospital number (unique to the patient) , Address etc.)</li>
                <li>date of surgery</li>
                <li>hospital site</li>
                <li>surgeon</li>
                <li>intervention or operation type (this will attract a certain set of questionnaires at set times)</li>
                <li>Side of operation if appropriate</li>
                <li>PROMs scores (questionnaire responses) on various dates – at varying time points from the surgery/intervention.</li>
              </ul>
              <p>There is a large variety of potential questionnaires – many of them specific for specific operations/interventions. For each operation/intervention we will aim to collect specific information. Different operations/interventions would have different questionnaires collected at different times. For example for knee surgery we would collect the following:</p>
              <ul>
                <li>Pre-op knee score questionnaire</li>
                <li>Pre-op EQ5D questionnaire</li>
                <li>Knee score at 6 months post op questionnaire</li>
                <li>Knee score at 12 months post op questionnaire</li>
                <li>EQ5D at 12 months post op questionnaire</li>
              </ul>
              <p>Thus we need the ability to define which operation/intervention attracts which scores and when, so they are automatically “asked” at the right time in the patients journey through healthcare.</p>
              <p>The first build including the Foot &amp; Ankle module is completed and has basic functionality for inputting patient and procedure data listed above. This is now being tested internally at Northumbria Healthcare. There will also be the facility for a basic data export into Excel for analysis. Phase II will add other specialty modules and further functionality. Orthopaedic questionnaires to be included in the build are:</p>
              <ul>
                <li>Foot &amp; Ankle – MOXFQ, AOS, AOFAS, SAFAS, VISA-A, ATRS (Completed. Phase I)</li>
                <li>Upper Limb – OSS, OSIS, OES, Boston, PEM, URAM, QDash</li>
                <li>Hip – OHS, iHOT12, NAHS</li>
                <li>Spine – NDI, MDI, ODI, VAS back &amp; leg, VAS arm &amp; neck</li>
                <li>Knee – OKS, OKS (A&amp;P), KOOS, Tegner, IKDC</li>
                <li>General MSK - MSKHQ</li>
                <li>General &nbsp;health– EQ-5D, Pain VAS, Patient Satisfaction</li>
              </ul>
              <p>Once the initial package above is working there are many potential extras that we would like to have going forward, including:</p>
              <ul>
                <li><b>Additional methods to input outcomes</b></li>
                  <ul>
                    <li>Tablets or PC browser entry by the patients in clinic within the hospitals intranet</li>
                    <li>Web and smartphone / tablet entry via the internet</li>
                    <li>Text responses</li>
                    <li>The ability for the software to generate bar coded questionnaires so they can be automatically posted out to patients and automatically read when returned, and ascribed to the correct patient and operation/intervention.</li>
                  </ul>
                <li><b>Additional functionality</b></li>
                  <ul>
                    <li>Automatic prompts when post-operative responses are due</li>
                    <li>Prompts when questionnaires have not been received</li>
                    <li><b>Reporting module</b></li>                
                    <li>Ability to analyse data and view charts, graphs, and tables with a variety of queries possible. This will allow real time data to be available to clinicians and teams within hospitals.</li>
                    <li><b>Data push into national registries</b></li>
                    <li>Ability to push data into the various national registries to avoid duplication and save time.</li>
                  </ul>
              </ul>
              <p>Contact Anji Kingman</p>
              <div class="row">
                <ul>
                  <li><a href="mailto:angela.kingman@northumbria-healthcare.nhs.uk"><i class="fas fa-envelope fa-2x sr-contact"></i></a></li>     
                  <li><a href="https://twitter.com/outcomes_proms"> <i class="fab fa-twitter fa-2x sr-contact"></i></a></li>
               </ul>
              </div>
                
          </div>
      </div>
  </div>
</section>
