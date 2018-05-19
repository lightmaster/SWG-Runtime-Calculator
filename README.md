# SWG-Runtime-Calculator

Link to TroubleFreePool's forum post: [SWG Run Time Calculator - TFP Forums](https://www.troublefreepool.com/threads/122980-SWG-Run-Time-Calculator "SWG Run Time Calculator")

## Screenshot
[![SWG_Runtime_Calculator_screenshot.png](https://s26.postimg.cc/qb4d7b0x5/SWG_Runtime_Calculator_screenshot.png)](https://postimg.cc/image/51gqwgkmd/)

## Instructions
1. Enter your Pool Size in D6
2. Enter your average 24 hour FC demand in D7
3. Enter your 24 hour FC output in D8. See [Discount Salt Pool SWG Comparison](http://j.mp/SWGClProduction) for common SWG's "Power (lbs/day)".

You can adjust the "SWG Output %" to see how many hours you need to run to run your pump. You can type in a desired runtime to see what percent you need to set your SWG to. You can also look at the chart that shows the number of hours your pump needs to run based on percents in 5% increments and an FC demand between 1 and 5.

# Build from source
The spreadsheet is saved as a decompressed folder in Github to conserve space. As a compressed xlsx file, Github has to store a new full copy of the spreadsheet, even if you change just 1 byte. These directions will help you repackage it back into an Excel spreadsheet if you want to try out the latest spreadsheet before its released.

_With each release, the actual spreadsheet will be published as well, downloading and using the source code is only for if you want to help out._

## Convert to .xlsx
1. Navigate into the project folder and into the "SWGCalculator" folder.
2. Select the \_rels, docProps, xl, and [Content_Types].xml folders
3. Right click and hover over "Send to", then click "Compressed (zipped) folder"
4. If you can't see the ".zip" extension, go into your "Folder Options" and enable showing extensions for known filetypes.
5. Rename the zip file to "SWGCalculator.xlsx"

## Decompress back to source
1. Navigate into the project folder and into the "SWGCalculator" folder.
2. Rename "SWGCalculator.xlsx" to "SWGCalculator.zip"
3. Right click on "SWGCalculator.zip" and select Extract All...
4. Remove the final "SWGCalculator" from the path and hit "Next" (ie it should look like "location\SWG-Runtime-Calculator\SWGCalculator")
5. Select that you want to merge any folders and you'd like to "Copy and Replace" any files.
6. Delete "SWGCalculator.zip" file.

If you use 7zip instead of Windows archive software, select to "Extract Here"
