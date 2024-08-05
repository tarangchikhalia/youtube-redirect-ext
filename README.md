# Youtube Redirect Extension
This is a simple chrome extension to redirect the traffic to https://youtube.com to https://youtube.com/feed/subscriptions.

## Todo list
- Setup navigation.onnavigate to intercept the event in the site. 
- Add a section in the extension to select the categories and only show youtube videos for that categories.

## Limitation
- this won't work with links inside the site because YouTube uses "soft navigation" (the same page is shown but its contents and the address are changed through JS).