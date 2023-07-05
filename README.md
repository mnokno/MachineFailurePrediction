# MachineFailurePrediction

Predicting failure of mechanical machines based of various sensor measurements and machine features/characteristics.

Features available in the dataset:
- Production Id: Unique Id, combination of Type variable followed by a number identifier
- Type:	Type of product/device (L/M/H)
- Air Temperature: Air temperature in Kelvin
- Process Temperature: Production process temperature in Kelvin
- Rotational Speed:	Speed in RPM (Rotations Per Minute) calculated with the power of 2860W
- Torque: Torque in Nm (Newton Meter)
- Tool Wear: Time unit needed to wear down the product/tool
- Machine Failure: Machine Failure binary feature
- TWF: Tool Wear Failure binary feature
- HDF: Heat Dissipation Failure binary feature
- PWF: Power Failure binary feature
- OSF: Overstate Failure binary feature
- RNF: Random Failure binary feature

Kaggle Competition: https://www.kaggle.com/competitions/playground-series-s3e17  
Kaggle Notebook: https://www.kaggle.com/code/mnokno/machine-failures-visual-eda-simple-submission  