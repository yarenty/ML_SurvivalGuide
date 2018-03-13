Mobile Data Challenge
---------------------


# DATA
[TRAIN data](data/train.zip)

- ip: ip address of click.
- app: app id for marketing.
- device: device type id of user mobile phone (e.g., iphone 6 plus, iphone 7, huawei mate 7, etc.)
- os: os version id of user mobile phone
- channel: channel id of mobile ad publisher
- click_time: timestamp of click (UTC)
- download_time: if user download the app for after clicking an ad, this is the time of the app download
- is_downloaded: the target that is to be predicted, indicating the app was downloaded

*Note that ip, app, device, os, and channel are encoded.*

# GOAL
Objective is to predict whether a user will download an app after clicking a mobile app advertisement.

Evaluation on [area under the ROC curve](http://en.wikipedia.org/wiki/Receiver_operating_characteristic) between the predicted probability and the observed target.

