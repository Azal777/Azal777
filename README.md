pening Webdriver
==> New Image: https://scontent.fisb5-2.fna.fbcdn.net/v/t39.30808-1/cp0/p74x74/234303681_166685532223710_
-> Inserting Image URL
==> Please agree to google's stuff in the browser
Traceback (most recent call last):
File "/home/bassam/EagleEye/eagle-eye.py", line 229, in 
main(skipFB=args.skipfb, FBUrls=[], jsonRep=jsonRepFile, dockerMode=aDocker, dockerName=aName)
File "/home/bassam/EagleEye/eagle-eye.py", line 128, in main
g.collectLinks(img)
File "/home/bassam/EagleEye/grabber/google.py", line 76, in collectLinks
elems = driver.find_elements_by_xpath(self.PHOTO_XPATH)[0]
IndexError: list index out of range

It gives this error when it comes to google search
