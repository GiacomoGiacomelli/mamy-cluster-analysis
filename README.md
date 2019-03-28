# mamy-cluster-analysis

Available Files:

Elyra_Table_example: 
- Index
- First Frame: Frame at which an event firstly appear
- Number Frames: (relevant only when grouping)
- Frame Missing: (relevant only when grouping)
- Position X [nm]: (0 to 51200)
- Position Y [nm]: (0 to 51200)
- Precision [nm]
- Number Photons
- Background Variance
- Chi square
- PSF half width [nm]
- Channel: relevant only for dual color
- Z Slice: relevant only for Z stacks 

Script_R1_ROI_mod (ROI modification script):
- Input: ROIs obtained via Fiji -> need to be named Cell*.txt
- Output: ROIs ready to be used for "PALM data analysis" script -> R.Cell*.txt

Script_R2_PALM analysis (PALM data analysis):

PALM_analysis_output example: (first 13 columns are the same as the "Elyra_Table_example")
- CellName: ROI file name (R.Cell*.txt)
- CellDiameter: Diameter of the ROI in nm
- CellArea: Area of the ROI in square nm
- ClusterName: Name of the cluster to which the event belongs (Cluster.X)
- ClustSize: Number of events associated to the cluster
- LocalDensity: Number of events in a squared area centered around the event (50nm side)
