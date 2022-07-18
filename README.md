# ipacheck


## Installation

```Stata
* ipacheck may be installed directly from GitHub
net install ipacheck, from("https://raw.githubusercontent.com/c4ed-mannheim/ipa_hfc_v3/master/ado") replace 

* after initial installation ipacheck can be updated at any time via
ipacheck update

* to start a new project with folder structure and input files
ipacheck new, surveys("SURVEY_NAME_1") folder("path/to/project")

* when starting a new project with multiple surveys, you can choose to use the subfolders option to create subfolders for each survey
ipacheck new, surveys("SURVEY_NAME_1" "SURVEY_NAME_2") folder("path/to/project") subfolders

* to obtain fresh copies of the master do-file and Excel inputs without creating the folder structure
ipacheck new, files

* to go through IPA's exercise with instructions, exercise data, and folder structure with input files
ipacheck new, exercise 

* to verify you have the latest versions of the commands
ipacheck version
```
If you encounter a clear bug, please file a minimal reproducible example on [github](https://github.com/PovertyAction/high-frequency-checks/issues). For questions and other discussion, please email us at [researchsupport@poverty-action.org](mailto:researchsupport@poverty-action.org).

## Authors
 - Christopher Boyer
 - Caton Brewster
 - Kelsey Larson
 - Ishmail Azindoo Baako
 - Isabel Onate
 - Rosemarie Sandino

