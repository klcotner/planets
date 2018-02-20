# hw_3 README

## HOUNDIFY
For speech-to-text, I'm using the Houndify Python SDK, found [here](https://www.houndify.com/sdks#python)

In order for this notebook to work:
1. ensure the path to your download of the Houndify SDK is on your system path
2. set up your Houndify account
3. set up a Houndify client with speech-to-text enabled
4. enter the client ID and key in the file `p1_userinfo.py` (user ID can be anything)

## EMAILS
The restricted Gmail SMTP server can only send mail to Gmail or G Suite users
* see [Google support page](https://support.google.com/a/answer/176600?hl=en)
* It works to send mail to either `@gmail.com` or `@berkeley.edu`
* However, it can only send email from `@gmail.com`

In order for this notebook to work:
1. set your email address info in the file `p1_userinfo.py`
2. set a gmail address as `EMAIL_SENDROM`
3. set either a gmail or berkeley address as `EMAIL_SENDTO`

#### NB:
For some reason, the SMTP server worked just fine on campus, but didn't work on my home network. In the notebook, I included a screenshot showing some of the emails I successfully sent to myself using Monty

## PATH TO SOUND FILES
Please provide the path to the `sound_files` folder on your computer
	(or whatever folder you have the test files for problem 2)
1. set this path in the file `p1_userinfo.py`
