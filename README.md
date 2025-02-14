# Tracking Group-Leader social interactions
Released code for the paper "Towards robots reasoning about group behavior of museum visitors: Leader detection and group tracking".
https://content.iospress.com/articles/journal-of-ambient-intelligence-and-smart-environments/ais467

This code is open-source and free for anyone to experiment further with it :-) 
If you publish any work that uses this software or refers to it in any way, please just cite us:

Trejo, K., Angulo, C., Satoh, S. I., & Bono, M. (2018). Towards robots reasoning about group behavior of museum visitors: Leader detection and group tracking. Journal of Ambient Intelligence and Smart Environments, 10(1), 3-19.

## Requisites
- OpenCV 2.4.11
- Dlib 18.18 (not mandatory to run the executable)
- Visual Studio 13 (C# environment)
- An input video sequence (.avi or .mp4 file)

## How to use
Just run the .exe file from the directory of any version (*group_leader_traker* or *exponential_group_leader_traker*) in command line as: **chosen_version.exe path_to_your_video_file.avi**

If you want to edit any of the source code, add the desired version of *Source.cpp* file to a Visual Studio project with the corresponding .prop files --for OpenCV and DLib-- to your project path by importing the contents of *libraries* directory. Remember to add the paths to DLib and OpenCV to your project environment as well. 

In case you are willing to prepare ground truth to validate your experiments, uncomment the corresponding section in the source files of *group_leader_traker* and *exponential_group_leader_traker* to capture the frames that will be analyzed further. Adapt the frame sampling rate to your own needs.

We cannot provide the image-video datasets from our paper. However, you can still watch the algorithm in action for the Miraikan museum video sequences at https://www.youtube.com/watch?v=gb8dIY-UiTg&t=2s

## Contact
Please leave a comment in my YouTube channel or ResearchGate page* if you have any questions or require assistance of any kind. I'll be glad to help!

*https://www.researchgate.net/publication/322609811_Towards_robots_reasoning_about_group_behavior_of_museum_visitors_Leader_detection_and_group_tracking/comments
