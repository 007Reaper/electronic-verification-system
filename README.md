# electronic-verification-system
Project files for a system I have recreated in order to solve identified issues with current hardware/software at my work environment.

## Background:
Upon being employed to support a system which allows for the end-users to scan, verify and update assets by means of barcode scanning devices, and a standalone laptop, that utilize a software created on the windows mobile platform and windows 7 operating system respectively, which are as of now end of life. I have been faced with compatibility challenges, and faced with issues where the service provider of the initial software could not develop a newer updated system, nor is there any support for such a system.

Due to my personal position of support of the system, I have had the opportunity to understand the complete working of the system, and have taken it upon myself to create a possible solution that addresses all the issues being faced, namely, the cost of equipment, the speed and efficiency of the system, and the ability to maintain the system.

I have then purchased an inexpensive barcode reader input device, and have begun working on a possible first draft of a system written on python, which would address all of the issues, as well as work interchangeably with the current input dataset such that a possible transition to my system can be done with no additional costs.

After having successful results with the desktop draft variant, I have then focused my efforts to rebuilding the system on the android platform, which will still address all of the issues, as well as allow for greater mobility, lower cost of future equipment, and remove the need for specific equipment such as a barcode scanner as the android devices are versatile and most devices as of today come prebuilt with a local camera which could be utilized to scan barcodes.


## Outcomes
While practicing, testing, and debugging, I have successfully built the android demo of the software, which can perform the most fundamental tasks such as the initial system, namely, reading the same input data as that of the actual system, and allowing for user access, thereafter allowing for the end user to scan an asset barcode with a mobile device camera, using the Google ML kit API, which then tests against the input data to see if the scanned item exists on the register, and gives the user options on what to do with the result.

## Final Remarks
The project still has much to be implemented, I do have future ideas for the system, however, I have not been requested as of yet to finalize the system for actual use, so the project has been halted until the work environment requires a solution to be presented.


