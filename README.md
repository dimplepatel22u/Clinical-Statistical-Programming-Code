# Clinical-Statistical-Programming-Code
This is my sample code for creating an SDTM-compliant AE dataset, an AE shell, a TLF from an ADSL dataset, etc.

I practiced SAS coding on 'dummy' or fake clinical trial data that mimicked a placebo-controlled, double-blinded interventional study
that focused on a treatment for ovarian cancer.

Clinical trials gather information via CRFs, or case report forms. I imported a sample CRF's information/data/variables using PERL language
via SAS. This data acquisition usually conforms to CDISC'S CDASH methods.

Typically, raw clinical trial data needs to be converted to SDTM-compliant datasets per CDISC standards for eventual FDA approval. I achieved
this via a 3-pronged approach: 1) I imported metadata about the SDTM dataset (say, for Adverse Events domain). 2) Then I created a custom
format library. 3) Moreover, I used the metadata to gather information to create a skeletal or a shell SDTM-compliant dataset (AE shell). 4) I then cleaned
the raw data typically inputted via CRFs and applied formats in the custom library to make sure SDTM guidelines are followed. 

Another part of the clinical trial data submission is AdAM datasets. I created a shell for the ADSL dataset. Then I created a  'Table/Listing/Figure' from
an already-created AdAM dataset.

I'm learning as much as I can about clinical and statistical programming. If you have any recommendations for more solid code, please reach out! Thanks!
