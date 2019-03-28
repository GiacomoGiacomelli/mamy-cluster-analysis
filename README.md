# mamy-cluster-analysis

Available Files:

PALM table example: 
- Index
- First Frame: Frame at which an event firstly appear
- Number Frames: (relevant only when grouping)
- Position X [nm]: (0 to 51200)
- Position Y [nm]: (0 to 51200)
- Precision [nm]
- Number photons
- Background Variance
- Chi square
- PSF half width [nm]
- Channel: relevant only for dual color
- Z Slice: relevant only for Z stacks 

ROI modification script:
- Input: ROIs obtained via Fiji -> need to be named Cell*.txt
- Output: ROIs ready to be used for "PALM data analysis" script -> R.Cell*.txt

PALM data analysis
