# UCLA Stats 101C Class Final Competition

### Team Limit DNE: Yanhua Lin, Yerin(Hana) Lim, Yingzhen Zhao

## Motivation 
Predicting the growth rate of YouTube videos 

## Description 
YouTube is a large scale video-sharing platform owned by Google since late 2006. The site allows users to upload, view, rate, share, create playlists, comment on videos, and subscribe to other users. Of these interactions, views stand out as particularly important because they are a direct measure of engagement with a video and also help to determine how much revenue the content creator will make. A pressing goal for a content creator is to know how fast a video will grow, especially within the first few hours of its lifetime. A video’s early growth pattern can be a broader indicator of the eventual success of the video as well as the overall health of the channel.

In this project, we aim to predict the percentage change in views on a video between the second and sixth hour since its publishing. In order to predict this metric, we have several video features at our disposal, generally fitting into four categories: Thumbnail Image Features, Video Title Features, Channel Features, Other Features. 

Raw dataset contains 7242 videos and 258 predictors. 

## Technologies Used
R 

## Evaluation (Scoring metric) 
Root Mean Square Error (RMSE) measuring the distance between predicted growth percentage and the true growth percentage.

## Codes
main codes are in the rmd file. 
report is also included in the pdf file. 
Our final presentation can be found in youtube: https://www.youtube.com/watch?v=sZxqn6EQNjg

## Results 
Our team won 1st place with the RMSE of 1.37819. 
