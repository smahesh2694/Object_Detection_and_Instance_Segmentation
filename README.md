# Object_Detection_and_Instance_Segmentation

**Instance segmentation on stereo vision images of KITTI dataset, using YOLOv3 object detector and depth data.**

NOTE: Please upgrade to the latest opencv version to avoid errors.

1. Kindly create new folders inorder to save results.
	<ul>
		<li>data/test/est_depth</li>
		<li>data/test/yolo</li>
		<li>data/test/est_segmentation</li>
	</ul> 
	
2. The bounding boxes are saved as numpy arrays and accessed later 
during the instance segmentation process. So it's important to follow step 1.
