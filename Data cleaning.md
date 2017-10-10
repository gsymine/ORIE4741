APR MDC Code is less specific than CCS diagnosis code - maybe filter on APR MDC Code first to get the most frequent diseases.

Age group from range to ordinal number.

Type of adimission to ordinal number

Patienet disposition (condition of patient at discharge) to ordinal number.

Add a column named 'Patient Disposition Indicator' with values: 
  Home or Self Care                             18;
  
  Home w/ Home Health Services                  17;
  
  Skilled Nursing Home                          16;
  
  Expired                                       15;
  
  Inpatient Rehabilitation Facility             14
  
  Short-term Hospital                           13
  
  Left Against Medical Advice                   12
  
  Hospice - Medical Facility                    11
  
  Hospice - Home                                10
  
  Psychiatric Hospital or Unit of Hosp           9
  
  Facility w/ Custodial/Supportive Care          8
  
  Another Type Not Listed                        7
  
  Medicare Cert Long Term Care Hospital          6
  
  Court/Law Enforcement                          5
  
  Cancer Center or Children's Hospital           4
  
  Hosp Basd Medicare Approved Swing Bed          3
  
  Federal Health Care Facility                   2
  
  Medicaid Cert Nursing Facility                 1
  
  Critical Access Hospital                       0
 

check wheter APR risk of mortality == APR severity of illness ? use APR severity of illness code for both columns

APR medical surgical description - maybe convert to boolean (0 for medical, 1 for surgical)

CCS procedure code indicates treatments.
