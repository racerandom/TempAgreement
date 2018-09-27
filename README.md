# TempAgreement
* Please install the python library (implemented by Thomas Grill) for calculating Krippendorff’s alpha before executing our code.  
  clone https://github.com/grrrr/krippendorff-alpha into a folder
  run "python setup.py install" in the folder

* Edit "TempAgreement.py" to assign "annotator1_dir" and "annotator2_dir" with the absolute paths of two folds including annotation in the main function.

* run "python TempAgreement.py"


The results will show the agreement ratio for each timeml file. Overall krippendorff_alpha and agreement numbers will be listed in the final.

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
