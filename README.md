# Moderating-Social-Media-using-AI

covering further ground by invoking libraries from the UiPath marketplace, UiPath Go!, and creating our first artificial intelligence (AI)-based automation!

We will learn how to automatically moderate images that are uploaded to social media sites. This type of automation will process images using the Google Cloud Vision API and send the administrator a spreadsheet with its recommendations.

Once the bot detects that new files have been uploaded, it reads each file and creates an Excel log to pass to the administrator. It then loops through all the image entries in the spreadsheet and invokes Safe Search in the Google Cloud Vision API to check the images. The API returns an output that indicates whether the image contains adult, medical, violent, or racy content. We add this output to Excel and send this to the administrator for him/her to take the appropriate action.
