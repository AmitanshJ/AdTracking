The Kaggle challenge was to predict if the user will install the app while viewing the advertisement. The target variable is_attributed indicates if the app is downloaded. The data was collected based on every click user perform on the interface. The data consists of 200 million clicks in just 4 days and the results were evaluated based on ROC while the final predictions were evaluated with hidden test set.


There were multiple columns such as 
ip: ip address of click.
app: app id for marketing.
device: device type id of user mobile phone (e.g., iphone 6 plus, iphone 7, huawei mate 7, etc.)
os: os version id of user mobile phone
channel: channel id of mobile ad publisher
click_time: timestamp of click (UTC)
attributed_time: if user download the app for after clicking an ad, this is the time of the app download
is_attributed: the target that is to be predicted, indicating the app was downloaded
