**Create an app which downloads multiple videos**

Create a single screen app which will download multiple videos simultaneously and store the video file in local directory to be accessed during offline


<img width="379" alt="Screenshot 2022-03-02 at 8 57 40 PM" src="https://user-images.githubusercontent.com/21215442/156393632-3654fdbd-ffb0-4c4c-9691-596037423194.png">


**Design and Functionality**

1. Using Table view List all the videos according to the attached design.
2. You can wite your custom title like Title 1, Title 2 etc..
3. For each cell when video is not downloaded show download button 
4. Generate thumbnails from video url to display for each cell as per design. 
5. When user clicked on download button, start downloading the video and show the download progress as per the UI design 
6. User can delete the downloaded video so when video successfully downloaded, show delete button to delete video from documents directory
7. Show retry button when video failed to download and show the alert for reason for failure
8. On tap cell, play the video using system player once the video is downloaded. 
9. Since these are large video file sizes, it might take time to download all video simultaneously, so the user might switch to a different app or lock the phone. So if you manage to continue video download even in the background (suspended state) is highly appreciated. 


**Video URL**

use below direct urls to download the videos 

1. https://player.vimeo.com/external/451569305.m3u8?s=c7da8176e60471cc9c51156ae3f35fc2c62ce72f
2. https://player.vimeo.com/external/433925279.m3u8?s=8930e1062fd90896c870a234a018a66ef544e74d
3. https://player.vimeo.com/external/432904528.m3u8?s=2eea9d6430a2ee2c760701e34178352b693b3f1b
4. https://player.vimeo.com/external/432902374.m3u8?s=ca1aabae12ccb24bfb83def94fa3ee6e38d939ae
5. https://player.vimeo.com/external/433664412.m3u8?s=a511c3907db8d1832de247987b28ce1ac788763b


**Video Reference**


https://user-images.githubusercontent.com/21215442/156404211-c3b8e636-c024-40d2-84e6-3f3069e1fc17.mp4



