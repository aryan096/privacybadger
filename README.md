# Privacy Badger without blocking but all the tracking

This is a modified version of PrivacyBadger that allows the extension to capture information about all the trackers it sees in your browsing but doesn't block any of them. Disabling PrivacyBadger from blocking trackers is useful because the downloadable user data is then an accurate history of trackers found in your browsing. 

## Installation
1. Clone this repo
	`git clone https://github.com/aryan096/privacybadger.git`
	
2.  Remove any previous install of PrivacyBadger you might have on Firefox or Chrome

3. Install this unpackaged version of PrivacyBadger in either Firefox or Chrome 

	#### Firefox - 
	a. Open the about:debugging page (type 'about:debugging' in the url box)
	b. click "This Firefox"
	c. click "Load Temporary Add-on"
	d. select any file in your extension's directory
	e. The extension will now be installed, and will stay until you restart Firefox.

	#### Chrome - 
	a. Open the chrome://extensions page (type 'chrome://extensions' in the url box)
	b. Enable developer mode
	c. Click on Load Unpacked
	d. select the src folder
	e. The extension will be installed now.

4. Open PrivacyBadger settings 
5. In General Settings, enable "Learn to block new trackers from your browsing"
6. In General Settings, disable "Send websites "Global Privacy Control" and "Do Not Track" signals".
7. In Manage Data, remove all tracking domains
8. You're done! Now go browse around and when you're ready, go to Manage Data and export user data. You should now have a .json file with a history of all the trackers that were found throughout your browsing mapped to the websites they were found on. 


