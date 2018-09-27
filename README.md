# TempAgreement
* Please install the python library (implemented by Thomas Grill) for calculating Krippendorff’s alpha before executing our code.
  pip install krippendorff

* Edit "TempAgreement.py" to overwrite "annotator1_dir" and "annotator2_dir" in the main function. "annotator1_dir" and "annotator2_dir" are the absolute paths of two folds including annotation.

* run "python TempAgreement.py"


It will show the agreement ratio for each timeml file. Overall krippendorff_alpha and agreement numbers will be listed in final.

## Example results:

Processing timeml file: AQA017_APW19990410.0123.tml  
agreement per doc: 0.4595  

krippendorff_alpha (nominal metric): 0.442  
Agreed number: 133  
 Agreed single: 122  
 Agreed multi: 11  
 Disagreed number: 155  
 -Both single (Disagreed): 50  
 -Both multi (Disagreed): 44  
 --Agreed begin (Disagreed multi): 14  
 --Agreed end  (Disagreed multi): 8  
 -Other (Disagreed): 61  
 Total: 288  
 Total disagreement: 0.5382  
