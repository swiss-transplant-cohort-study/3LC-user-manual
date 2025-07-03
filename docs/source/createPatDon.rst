3. Create...
##############

There are two ways to register a patient. First navigate to *Create and Search* and select either:

* **Patient Enrollment**: register a patient who has enrolled in the STCS study already (i.e. the patient has already received a transplation) - red circle -, or
* **Patient Registration**: register a patient who has not yet received a transplant - green circle.

.. image:: PatPaths.png
   :width: 600

.. note:: The Ethics Committee has approved the registration of waitlisted (not yet transplanted) patients in the database. The recorded information includes current consent status. However, no collection of clinical/research data is allowed before transplantation. Proper enrollment in the Cohort only starts at the time of transplantation.

.. tip:: Check :ref:`consent` for more details.

.. warning:: The patient should be entered in the database within 7 days after transplantation (5 working days). The minimal entry should containt: name, first name, date of birth and consent status with date.

The following fields are common between **Patient Enrollment** and **Patient Registration**:

Administrative data
***********************

The first step is to add the administrative data for the patient, such as:

* Initials: use the intial of each name in uppercase, with "-" as separator between the First name initial/s and Last name initial/s. Examples: Georgios Kyriakos Panayiotou -> GK-P, Rosa Dolores Alverío Marcano -> RD-AM. When family names include particles are treated as a further Family name: e.g.Charles De Gaulle -> C-DG, Miguel De Oliveira -> M-DO.
* Gender at birth
* Date of birth
* Blood group

.. image:: AdminData.png

Once this is filled in, please proceed by clicking "Save and add Cons". A STSC Patient ID will be automatically generated once the Adminstrative data is saved.

.. tip:: The date of birth can also be manually typed.

.. tip:: When selecting the date of birth, if you click on the "Month", a month view appears. If you further click on the year, a year view appears. This will help you navigating through time and selecting the right date of birth more easily.

3.1 Create donor enrollment
************************

(in construction)

3.2 Create patient enrollment
**************************

(in construction)

3.3 Create patient registration
****************************

3.3.1. Create consent
==========================

Consent management
---------------------

Here, you can see the STCS ID for the just created patient. Equally, the age of the patient is displayed - this is important, as the patient might need to re-consent. The patient might need to re-consent due to a variety of situations, such as: patient is under 18 at the time of the transplantation, patient was not able to give consent at the time of transplantion, etc. For example, in the case of the patient 90000034, age 14, the default re-consent is set to "Yes" (and it can not be edited), as shown below. If the patient was an adult, the default re-consent would be set to "No". 

.. image:: ConsentFields.png

.. warning:: Is the patient a candidate to be re-consented? Yes if it is a minor (<14 years) and the parents signed7refused the first consent.

Consent status
----------------
Here are the different consent fields:

* Consent "Present": when consent is present. In case of a signed consent form choose this option and fill in the consent date (date indicated on the informed consent and the IC form the patient or his parents or relatives signed.

.. note:: If you entered an ‘absent (awaiting)’ consent prior to an IC ‘present’ and you entered ‘minimal’ in data collection, be sure to change this to ‘full’ prior to enter the ‘present’ IC.


* Consent "Absent awaiting": there is no consent for the moment, but the consent has not been explicitly refused. In case you sent out the IC Form but did not get an answer yet, chose this option until you can update it to a ‘present’ or ‘absent (documented refusal)’.

.. tip:: In data collection choose full or minimal (according to your intern procedure management) and as consent date enter the date you sent out the IC. In the comment field enter the attempts to obtain the informed consent (e.g. phone call on 1.3.2025, reminder sent on 1.3.2025, etc.).

* Consent "Absent documented refusal": when the consent were explicitly refused by the patient. In case you get a written or oral (e.g. phone call) refusal of the participation in the STCS, enter this option.

.. tip:: As date enter the date on the letter or of the oral refusal. In the comment field enter the attempts to obtain informed consent and/or how was the refusal communicated.

.. note:: If you entered an ‘absent (awaiting)’ consent prior to an ‘absent (documented refusal)’ consent and you entered ‘full’ in data collection, be sure to change this to ‘minimal’ prior to enter the ‘absent (documented refusal)’ IC 

Please check :doc:`consent` for more information about the different types of consents and other information.

3.3.2. Create SOAS Listing
=============================

3.3.3. Create Transplantation
================================

3.3.4. Donors
===================

3.3.5. Non STCS Study Linkage
=================================
