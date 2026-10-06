# FootBall Game Analytics 

The system is designed to  perform football game analytics from the game videos.
Based on the video shots available it will be able to track and track the football.

## FootBall-Player Detected vidio
[Download Video](video/calculating_steps.mp4)

Detects every players in the field using the **YOLO based models**.
various SOTA YOLO models were used to establish the best performing model.

## Player Steps Calculated video
[Download Video](video/calculating_steps.mp4)
Players were initially detected by the detection model (instance segmentation model) and by using the **byte track** packages, the players **stride rates** were detected.

## Front-end Video
[Download Video](video/with_front_end.mp4)

**This innovative system addresses the challenges of implementing real-time sports analytics on resource-constrained devices like mobile or edge systems. By creating a meticulously annotated dataset and employing advanced techniques, we have validated the model's proficiency in effective real-time object detection and tracking. The result is a lightweight, flexible solution that offers accessible and efficient tracking of players and balls, even on limited-resource devices.**
