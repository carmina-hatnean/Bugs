# Bugs

Below are some Bug Reports samples that I wrote while working on previous projects.

------------
## Bug Report 1 

**Priority and severity**

P2 - High

**Description**

When trying to login with the correct credentials, nothing happens.

The user is not logged in and no error message is displayed.


**Steps to reproduce**

Go to www.website.com/login

Add a correct user/pass


**Expected result**

User should be able to login and is taken to his profile page.


**Actual result**

User is not logged and no error appears.



**Test data**

User: carmina & Pass: 123456

----------------------------------
## Bug Report 2 - Error in the browser console

**Priority and severity**

P4 - Normal

**Description**

When I go the website, I notice that it doesn't have a favicon and I discover an error in the console.

**Steps to reproduce**

1. Go to https://www.apulum.ro/
2. Type F12
3. Click on Console

**Expected result**

The users should see the favicon.

**Actual result**

The website have an error in the console "Failed to load resource: the server responded with a status of 404 (Not Found)". Favicon not showing up.

![favicon 1](https://user-images.githubusercontent.com/85248462/212406487-632528a2-171f-49f2-9011-dd9cb9b8b102.png)

----------------------

## Bug Report 3 - Page load too long time

**Priority and severity**

P4 - Normal

**Description**

When I trying to refresh the website this reloaded slow. The website resources are too large and this affects its performance.

**Steps to reproduce**

1. Go to http://www.primaria-constanta.ro/
2. Type F12
3. Click on Console
4. Check Preserve log
5. Check Disable cache
6. Check all
7. Type CTRL + F5

**Expected result**

The website should have a loading time of approximately 2 seconds.

**Actual result**

The website has a loading time of 9,74 seconds.

![bug - load time](https://user-images.githubusercontent.com/85248462/212410108-19020fd0-5900-4e83-8e5b-a47fdef303bb.png)

-----------------------
## Bug Report 4 - Broken Link

**Priority and severity**

P4 - Normal

**Description**

When I tried to click on the link 'www.e-licitacie.ro' from the website, it wasn 't working, so I checked if the website has broken links.

**Steps to reproduce**

1. Go to https://ahrefs.com/broken-link-checker
2. Type http://www.primaria-constanta.ro/ in the input field.

**Expected result**

The user expect that all the links on the website are working.

**Actual result**

The website have three broken links.

![Broken link](https://user-images.githubusercontent.com/85248462/212412710-e74802df-aacd-4fee-aac5-430631cce926.png)

--------------------------

## Bug Report 5 - 404 Page

**Priority and severity**

P4 - Normal

**Description**

When I tried to type in the URL 'http://www.primaria-constanta.ro/asdfghjkl' I discovered that the website doesn't have a customized 404 page.

**Steps to reproduce**

1. Go to http://www.primaria-constanta.ro/
2. Go to http://www.primaria-constanta.ro/asdfghjkl

**Expected result**

The users expected to have a 404 custom page.

**Actual result**

The website don't have a custome 404 page.


![404 page](https://user-images.githubusercontent.com/85248462/212414731-50a9c0f8-dfe0-42f7-8204-2db229a3e44b.png)

-------------------
## Bug Report 6 - Responsive

**Priority and severity**

P4 - Normal

**Description**

I tried to access the website from the phone and I discovered that it isn't responsive and the buttons and text are too small..

**Steps to reproduce**

1. Go to https://www.primariatechirghiol.ro/
2. Type F12
3. Click on Responsive Icon


**Expected result**

The users expected to have a responsive website.

**Actual result**

The website isn't responsive and can't be easily typed from the phone.

![not responsive](https://user-images.githubusercontent.com/85248462/212416126-fd5ea943-1c66-4bd3-b366-b2b10234e601.png)




-----------------
