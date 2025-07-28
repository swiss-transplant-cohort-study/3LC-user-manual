4. Baseline and Follow-up forms, including Samples and PSQ
################################################################

.. image:: FUP1.png

The ‘Patient FUP’ and ‘Organ FUP’ are short overviews with toggles that allow to enter a “yes”, “no” or “missing” for all collected information groups in the ‘Patient Diagnosis List’ and the ‘Organ’.

.. image:: FUP2.png

The assessment containers are color-coded, see picture below:

* Container with white fill, black outline: created baseline or FUP without entered data
* Container with white fill, green outline: data collection is ‘in progress’
*	Container with white fill, blue outline: ‘Minimal’ dataset collection is complete
*	Container with white fill, red outline: Organ stop has been registered for that organ
*	Contianer with blue fill: Full dataset collection is complete

.. image:: FUP3.png

CRF status
*************

.. image:: CRF1.png
  :width: 500

The CRF status that appears on the Patient Overview can be chosen in the Baseline or FUP container at the top left. In order to save a form (bottom right side), a CRF status must be choosen.

Correction of a Follow-up date
================================

.. image:: CRF2.png

If you entered an incorrect follow-up date and you wish to correct this, then please proceed as follows:

#.	Go to Follow-up (see circle in the figure above).
#.	Choose ‘Edit’ the FUP you need to correct (see arrow in the figure above).
#.	Correct the date(s).

Deletion of a Follow-up date
================================

.. warning:: To delete a complete patient case, please contact the IT-departement (open a ticket with all relevant information).

If you added a FUP erroneously (e.g. in the false patient), you can delete the last added FUP by chosing ‘Delete’ (see red arrow) in the Follow-up overview.

.. image:: CRF3.png

Please note that already entered data in the ‘Patient Diagnosis List’, the ‘organ’ container’ and/or the ‘Lab’ container are not automatically deleted when deleting an added follow-up.

.. image:: CRF4.png

To delete the accidentally entered data, you have to delete them all manually. Access the corresponding container, press the ‘Delete’ (see arrow) in the row corresponding to the false entry and confirm your selection.

Assessment date
========================

The Date of assessment corresponds to the date when the visit was done to collect the patient data.
Baseline assessement date usually corresponds to the date of transplantation, and for FUP the date of the patient's cohort visit. 

4.1 Baseline forms
***********************

.. image:: BL1.png

.. warning:: All data, which occured prior to and up to transplantation, is considered baseline data. Hence this data will be entered in the patient and case baseline CRFs.

The patient baseline container consists of three sub-sections.
The first one, the ‘**Pre-enrolmennt history**’, corresponds to that what in the follow-ups is called ‘Post transplant diagnosis’ but will not collect ‘previous transplantations’ in follow-ups.
The ‘patient characteristics’ included in this section are referred as ‘Assessments’ in the follow-ups.

.. image:: BL2.png

The information in the second and third section (Patient HLA) is only collected once at the data collection of the first ever entered baseline, because it is data that does not change in time.

.. image:: BL3.png

.. image:: BL4.png

4.1.1. Pre-enrolment history
==================================

The toggles are only here to indicate wheter there was an event in the respective cathegory or not before the transplantation.

.. image:: BL5.png

To enter a specific event, click on the title of the event category (see red arrows). This will open the container in a new tab where you will be able to enter the corresponding event(s).

4.1.1.1 Infectious diseases
------------------------------

We do not collect the whole ID-History of the patient but only major pre-enrollment infectious diseases and infections active at the timepoint of transplantation.

More information regarding the collection of infectious diseases can be found in Patient containers/Patient Diagnosis List/Infectious Disease.

4.1.2. Patient characteristics
==================================

Please use to most recent measurements prior to transplantation. For the blood pressure, you can use the value in the anesthesia protocol or the last measurement prior to transplantation.
The BMI will be calculated automatically.

Questions
----------------

Baseline: Tobacco smoking habits:

*	Current: activates the question of ‘Number of pack years’.
*	Former: Activates the question of the date when the patient stopped smoking tobaco.

Baseline: Marihuana smoking habits:

* Current.
* Former: Activates the question of the date when the patient stopped marihuana

.. note:: Other illicit substance use: Indicate all illicit substances use until transplantation as a free-text.

4.1.3. Ethnicity
==================

In the drop-down list you can choose between ‘Caucasian’ (whiteness), ‘Asian’, ‘African or African American’ and ‘Other’. If you choose ‘Other’, please indicate the ethnicity in the comment field.

4.1.4. Past immunosuppressive treatment (including systemic corticosteroids)
==========================================================================================

A patient could have had an immunosuppressive treatment prior to transplantation for different reasons such as a previous transplantation, COPD or rheumatoid arthritis.

If a patient has received immunosuppressive treatments and/or systemic steroids in the past, select the appropriate treatment from the list:

*	IS treatment combined with systemic steroids.
*	IS treatment without systemic steroids.
*	Systemic steorids alone.

4.1.5. Patient HLA
========================

Patient HLA is registered here and only needs to be registered once, even if a patient recieves multiple transplantations (either combined or second or re-TX).

.. image:: BL6.png

If a HLA is homozygous, you can select the button next to the according HLA instead of searching for it in the second HLA-phenotype list.

Please indicate single missing HLA with the ‘x’, if all HLA is missing (analysis not done) select ‘All HLA missing’ to auto-complete all fields.
If you erroneously selected ‘All HLA missing’ you can undo that by clicking ‘HLA available’. Previously entered HLA will re-appear as long as you did not save the form..

4.2 Follow-up forms
*************************

.. iamge:: BL7.png

All events that occour after re-perfusion respectively from the first day after the last follow-up including the day of the actual follow-up are registered in the corresponding follow-up period.

The toggles are only here to indicate wheter there was an event in the respective cathegory or not before the transplantation.

.. image:: BL8.png

To enter a specific event, click on the title of the event cathegory. This will open the container in a new tab where you will be able to enter the corresponding event(s).

4.2.1. Post transplant Diagnosis
===================================

The toggles are only here to indicate wheter there was an event in the respective cathegory or not since the last assessment (baseline or follow-up).

.. image:: BL9.png

To enter a specific event, click on the title of the event cathegory. This will open the container in a new tab where you will be able to enter the corresponding event(s).

4.2.1.1. Infectious diseases 
----------------------------------

If you do not have (yet) information regarding the occourrence of an infection in the actual follow-up period, there might be different reasons for it. Please indicate the reason for the missing information in the drop down list and select from:

*	Awaiting confirmation
*	No information from external hospital available
*	No information from GP available
*	Patient death or drop-out
*	Patient did not attend follow-up visit
*	Other

.. image:: BL10.png

If you are awaiting the confirmation of possible IDs from a physician, you can leave the toggle on ‘-------’ and select ‘awaiting confirmation’ but be sure to leave the CRF status as ‘in progress’.
When you receive confirmation (or negation) of the suspected infection, do not forget to change the toggle to ‘Yes’ or ‘No’ and set the CRF status to complete. If needed, add the reported/confirmed ID in the ‘infectious diseases’ container.

More information regarding the collection of infectious diseases can be found in Patient containers/Patient Diagnosis List/Infectious Disease.

4.2.2. Assessments
=======================

Please use to most recent measurements prior to or on the day of follow-up.
The BMI will be calculated automatically.

Questions
---------------

The questions are just formal and no additional information to a ‘Yes’, ‘No’ or ‘missing’ is added anywhere.
Did the patient smoke tobacco since last cohort visit?


