Patient
########################

There are two ways to register a patient. First navigate to *Create and Search* and select:

* **Patient Enrollment**: register a patient who has enrolled in the STCS study already (i.e. the patient has already received a transplation)
* **Patient Registration**: register a patient who might not have yet received a transplant. 

..note:: The Ethics Committee has approved the registration of waitlisted (not yet transplanted) patients in the database. Registered information includes current consent status. No collection of clinical/research data is allowed before transplantation and proper enrollment in the Cohort only starts at the time of transplantation.

.. tip:: Check  :ref:`consent` for more details.

.. warning:: The patient should be entered in the database within 7 days after transplantation (two working days).

The following fields are common between **Patient Enrollment** and **Patient Registration**:

Administrative data
***********************

The first step is to add the administrative data for the patient, such as:

* Initials
* Gender at birth
* Date of birth
* Blood group

.. image:: AdminData.png

Once this is filled in, please proceed by clicking "Save and add Cons". A STSC Patoent ID will be automatically generated once the Adminstrative data is saved.

.. note:: Use the intial of each name in uppercase, with "-" as separator between the First name initial/s and Last name initial/s. Examples: Georgios Kyriakos Panayiotou -> GK-P, Rosa Dolores Alverío Marcano -> RD-AM. When family names include particles are treated as a further Family name: e.g.Charles De Gaulle -> C-DG, Miguel De Oliveira -> M-DO

.. tip:: When selecting the date of birth, if you click on the "Month", a month view appears. If you further click on the year, a year view appears. This will help you navigating through time and selecting the right date of birth.

Consent description
**********************

.. image:: ConsentFields.png

Consent management
====================

Here an option will be give to note whether the patient might need to re-consent or not.

Consent
===========

Here are the different fields:

* Consent:
  * Present: when consent is present
  * Absent (awaiting): there is no consent for the moment, but the consent has not been explicitly refused
  * Absent (documented refusal): when the consent were explicitly refused by the patient.
* Consent date
* IC form: different forms are available

.. tip:: Check  :ref:`consent` for more details.

Click "Save and continue" to further proceed.

Registration (SOAS Listing)
************************************


.. image:: patient_regi.png

.. tip::
   1. Register patient in STCS when you send Patient information to patient
   2. Add SOAS number and Organ
   3. Register consent as “Absent (awaiting)” with date when ICF sent out
   4. When you get consent form back then update consent with date
   5. Enroll patient only once transplanted (add transplantation and donor etc)


.. note::
   If the patient dies while on the waiting list, this information should not be entered in the system as it is a clinical data. The patient should 
   be left “open” in waiting list.



Enrollment
=======================

The transplantation is the event that triggers the patient enrolment.

.. image:: patient_enrol.png


Baseline
=========

- Clinical data

- PSQ

.. note::
   Reminder: As per email from Nadine Beerli sent out to LDM on March 7th, 2023, new PSQ schedule (Pre-Tx, 6 months post-Tx, 1, 3, 5, 7, 10 years 
   post-Tx and every 5 years thereafter) has been implemented as of April 1st, 2023.

Follow-up
==========

- Clinical data

- PSQ

Containers
============

- Transplantations before STCS enrolment
- Infectious diseases
- Cardio-pulmonary diseases
- Metabolic, endocrine and kidney diseases
- Skin cancers
- Neoplasia
- Other events and diseases
- Medication treatments
- Lab
- Stop (drop-outs and death)

.. note:: See :doc:`metadata` for list of collected data.

.. warning:: When a patient is created, it cannot deleted by an LDM. Please open a ticket to the IT.

More details can be found in our `Youtube page <https://www.youtube.com/watch?v=njswLTRGQII>`_.
