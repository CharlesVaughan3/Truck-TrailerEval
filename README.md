# Truck-TrailerEval
Summary of trucks and trailers that currently have problems and/or are in the shop.

This worksheet derives from another sheet known as Final_Project_DVIR_rollout_4.xlsm 
that is upkept by our shop. When they complete a DVIR in the shop it gets moved from the DVIR folder to the completed folder and this sheet can no longer see the issues. This program can also be found on https://github.com/CharlesVaughan3 

There are 4 differrent columns on the worksheet(truck#, trailer#, comments, and status). The program looks through every file and determines if "tractor defect?: yes" or "trailer defect?: yes" is a part of it. If either one catches it records either the truck#, trailer# , and then the comments and status. These text files that have both a truck and trailer problem will already be split into two seperate text files from a different program so that it does not conflict with when one is completed and the other is not. This makes it so when not both the truck and trailer is done we can complete the one that is and not lose the one that is not. We will make it so this worksheet will auto update(re run the program) every 15 minutes. The other worksheet being used by the shop in theory wll be continually updated meaning the operations center needs to have a current record of the trucks and trailers. 

The purpose of this program is for our disbatchers to have easy access to seeing which trucks/trailers they can not assign to drivers. 
It also saves time of the shop having to communicate with the disbatcher and gives them an easier time when a driver might ask them questions. There have also been some added pictures and formatting that contributes to how the user sees the information while promoting Stewart Transport with a couple of images(taken by our driver Beau). This is 

This program is useful for reading files and printing out specific lines that you want read. It also has functionality that removes the word that you search for in the text file so it will display only the part of the line you are looking for. 

If you are working with CRUD(Create Update Read Delete) with text files, this can be a great starting point. This would be especially useful to the user working with multiple text files. There are some really good coding practices in this excel project. Good luck!

I will keep this file updated as we roll out these programs, and see what issues arise, and what things might just not work so good or what might work better. This will be a long proccess of getting everyone to move over from papaer to a spreadsheet, which will take time but will be very beneficial in the long run. Im confident it will save plenty of time and effort for all employees. 

Any questions or concerns dont hesitate to contact Charles @ cvaughan@stewarttransport.com
