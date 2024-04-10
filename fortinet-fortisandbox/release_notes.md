#### What's Improved
- Added `Version` as a configuration parameter.
- Added a new action `Update Allow or Block List`.
- Added a new parameter `Decode Behavior File String` to the action `Get Job Behaviour`.
- Added a new parameter `Unzip File` in the action `Submit File` to unzip the uploaded before uploading to FortiSandbox. 
- Changed the output schema of the following actions:  
  - Get System Status
  - Get Scan Stats
  - Get Job Verdict Detail
  - Get Job Behavior
  - Toggle FPN State
  - Get PDF Report
  - Submit File
 
  - 

#### What's Fixed
- Fixed a bug where the playbook `File > FortiSandbox > Enrichment` failed if indicator did not contain a file.
- Fixed a bug where the action `Submit File` failed if the file IRI is provided as input in Indicator ID or Attachment IRI.
- Fixed a bug where the playbook `URL > FortiSandbox > Enrichment` failed with error message "Invalid params provided :: Parameters JSON Data have either blank value or not provided."
