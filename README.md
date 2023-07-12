# Bug report
------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## 1. Bug report https://www.demoblaze.com/

### => Title: Login with admin credentials
**Priority & severity**

P1 - HIGHT

**Description**

I can logged in with user & pass “admin“.

**Steps to reproduce**
1. Go to https://www.demoblaze.com/ 
2. Click to “Log in” button on the right corner
3. Fill the fields with username & password
4. Click on Log in button
   
**Expected result**

User should not be able to logged in with admin credentials.

**Actual result**

User can logged in with admin credentials.

**Test data**

user: admin & pass admin

### => Title: Order placed without any products
**Priority & severity**

P2 - MEDIUM

**Description**

I can place an order without adding any products.

**Steps to reproduce**
1. Go to https://www.demoblaze.com/cart.html# 
2. Assume that the cart is empty click on “Place order“ button
3. Fill the fields Name, Country, City, Credit card, Month, Year
4. Click on Purchase

**Expected result**

User should not be able to place an order without adding products.

**Actual result**

User can place an order without adding products.

**Test data**

Name: test
Country: test
City: test
Credit card: 1234 1234 1234 1234
Month: 6
Year: 2026

### =>Title: Browser incompatibility
**Priority & severity**

P3 - MEDIUM

**Description**

When accessing this link https://www.demoblaze.com/cart.html# on Opera or Edge it fills my cart with all the products.
Google chrome Version 114.0.5735.110 (Official Build) (64-bit)
Opera Version:99.0.4788.65
Edge Version 114.0.1823.43 (Official build) (64-bit)

**Steps to reproduce**
1. Go to https://www.demoblaze.com/cart.html# on Opera browser
2. Wait till all the products are entering on my cart

**Expected result**

The link should work the same as on Chrome.

**Actual result**

The link are not working properly on Edge and Opera.

**Test data**

https://www.demoblaze.com/cart.html#

=> Title: Error 404 modifying url
**Priority & severity**

P3 - LOW

**Description**

When I add something after https://www.demoblaze.com/  in URL it gives me an 404 error and I cannot longer navigate through site.

**Steps to reproduce**
1. Go to https://www.demoblaze.com/sdffffgsegqasssssssssssss 
2. Error 404

**Expected result**

Error 404 should not be visible and a button should appear with “back to store” or something like this.

**Actual result**

The link gave me error 404 and I cannot longer access the site.  

**Test data**

https://www.demoblaze.com/sdffffgsegqasssssssssssss

### =>Title: Console notification
**Priority & severity**

P4 - LOW

**Description**

Browser Chrome Version 114.0.5735.110 (Official Build) (64-bit)
When I open the console I have an error:
VIDEOJS: WARN: A plugin named "reloadSourceOnError" already exists. You may want to avoid re-registering plugins!
(anonymous)	@	video.min.js:12
n.warn	        @	video.min.js:12
i.registerPlugin @	video.min.js:12
(anonymous)	@	videojs-contrib-hls.min.js:8
77	                 @	videojs-contrib-hls.min.js:8
r	                 @	videojs-contrib-hls.min.js:1
e	                 @	videojs-contrib-hls.min.js:1
(anonymous)	 @	videojs-contrib-hls.min.js:1

**Steps to reproduce**
1. Go to  https://www.demoblaze.com/
2. Press F12
3. Go to Console

**Expected result**

This error should not appear.

**Actual result**

The error its shown.

**Test data**


### =>Title: Missing specification on a product
**Priority & severity**

P2 - MEDIUM

**Description**

Missing specification on a product it is replaced with REVIEW. 

**Steps to reproduce**
1. Go to https://www.demoblaze.com/
2. Scroll down at Sony vaio i7
3. Expected result
4. The product should have specification into description like other products.

**Actual result**

The product have no specification.

**Test data**


### =>Title: UI design on LOGIN button for mobile interface
**Priority & severity**

P3 - MEDIUM

**Description**

When you try to log in  from the phone you have USERNAME and PASSWORD fields too large.

**Steps to reproduce**
1. Go to https://www.demoblaze.com/index.html
2. Press F12 and press toggle device toolbar or press ctrl+shift+m
3. Press the login button

**Expected result**

Both fields USERNAME and PASSWORD should be on the line with login form.

**Actual result**

USERNAME and PASSWORD fields are larger than login form.

**Test data**


### =>Title: UI design on ABOUT US button for mobile interface
**Priority & severity**

P3 - MEDIUM

**Description**

When you click on “About us” button from the phone you have a video that is more larger than that form.

**Steps to reproduce**
1. Go to https://www.demoblaze.com/index.html
2. Press F12 and press toggle device toolbar or press ctrl+shift+m
3. Press the “About us” button

**Expected result**

The video should be on the line with “About us” form.

**Actual result**

The video is larger than “About us” form.

**Test data**


### =>Title: UI design on Contact button for mobile interface
**Priority & severity**

P3 - MEDIUM

**Description**

When you press “Contact” button, both fields “Contact Email” and “Contact Mail” are out of the form. 

**Steps to reproduce**
1. Go to https://www.demoblaze.com/index.html
2. Press F12 and press toggle device toolbar or press ctrl+shift+m
3. Press the “Contact” button

**Expected result**

Both fields “Contact Email” and “Contact Mail” should be on the line with “Contact“ form.

**Actual result**

“Contact Email” and “Contact Mail” fields are larger than “Contact“ form.

**Test data**


### =>Title: UI design on SIGN UP button for mobile interface
**Priority & severity**

P3 - MEDIUM

**Description**

When you click on “Sign UP“ on mobile interface both fields “Username” and “Password” are larger than the form.

**Steps to reproduce**
1. Go to https://www.demoblaze.com/index.html 
2. Press F12 and press toggle device toolbar or press ctrl+shift+m
3. Press the “Sign UP“ button

**Expected result**

Both fields “Username” and “Password” should be on the line with “Sign UP” form.

**Actual result**

“Username” and “Password” fields are larger than “Sign UP” form.

**Test data**


### =>Title: Buttons are not visible properly in mobile interface
**Priority & severity**

P3 - MEDIUM

**Description**

When you click on “Cart“ button on mobile interface the buttons are too close to Products and the “Log IN” and “Sign UP” buttons are not visible properly.

**Steps to reproduce**
1. Go to https://www.demoblaze.com/index.html 
2. Press F12 and press toggle device toolbar or press ctrl+shift+m
3. Press the “Cart“ button

**Expected result**

After you press the “Cart” button, the menu should be visible properly.

**Actual result**

“Log IN” and “Sign UP” fields are not visible properly. 

**Test data**


### =>Title: Oversized fields on "Place order" button in mobile interface
**Priority & severity**

P3 - MEDIUM

**Description**

When you click on “Place order“ on mobile interface the fields “Name“, “Country“, “City“, “Credit card“, “Month“, “Year“ are larger than the actual form.

**Steps to reproduce**
1. Go to https://www.demoblaze.com/index.html 
2. Press F12 and press toggle device toolbar or press ctrl+shift+m
3. Press the “Cart“ button
4. Press the “Place Order“ button

**Expected result**

All the fields should be on the line with “Place Order” form.

**Actual result**

All the fields are larger than “Place Order” form.

**Test data**


------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## 2. Bug report https://www.globalsqa.com/angularJs-protractor/BankingProject/#/login

### =>Title: The design is very small for mobile interface
**Priority & severity**

P1 - MEDIUM

**Description**

The design of application is very small on the phone interface, you cant even see properly.

**Steps to reproduce**
1. Go to https://www.globalsqa.com/angularJs-protractor/BankingProject/#/login 
2. Press F12 and press toggle device toolbar or press ctrl+shift+m

**Expected result**

Application should adapt for mobile interface and you should see properly all the buttons and texts from it.

**Actual result**

Application is very small on the mobile interface and you cannot see properly all the buttons and texts.

**Test data**


### =>Title: Login from URL
**Priority & severity**

P1 - HIGHT

**Description**

You can login into account modifying URL.

**Steps to reproduce**
1. Go to https://www.globalsqa.com/angularJs-protractor/BankingProject/#/login
2. Change “login“ from URL to “account“  https://www.globalsqa.com/angularJs-protractor/BankingProject/#/account

**Expected result**

You should not be able to login into account modifying URL.

**Actual result**

You can login into account modifying URL.

**Test data**

https://www.globalsqa.com/angularJs-protractor/BankingProject/#/account

### =>Title: Wrong button name
**Priority & severity**

P6 - LOW

**Description**

The button name “Withdrawl” should be “Withdraw“.

**Steps to reproduce**
1. Go to https://www.globalsqa.com/angularJs-protractor/BankingProject/#/customer
2. Select Harry Potter and hit “Login”

**Expected result**

The button name should be “Withdraw”.

**Actual result**

The button name is “Withdrawl”.

**Test data**

Harry Potter

### =>Title: Reset transaction log not working properly
**Priority & Severity**

P2 - HIGHT

**Description**

When you deposit for example 1500$ and withdraw 100$ and then you go to Transaction you should see all the transaction you made. If you want to clear the transaction you have no money left. 

**Steps to reproduce**
1. Go to https://www.globalsqa.com/angularJs-protractor/BankingProject/#/login
2. Click on “Customer Login”
3. Select Harry Potter an then click on “Log in”
4. Click on “Deposit” and write 1500 an then click on “Deposit” button
5. Click on “Withdraw” and type 100 and then click on “Withdraw” button
6. Click on “Transaction”
7. Click on “Reset” button
8. Click on “Back” button

**Expected result**

After you click on “Reset“ button on “Transaction” form you should not left out of money.

**Actual result**

After you click on “Reset“ button on “Transaction” form you are left out of money.

**Test data**

Harry Potter

### =>Title: Browser incompatibility
**Priority & severity**

P2 - MEDIUM

**Description**

When you are on Manager Account and click on Customer in Google Chrome browser you have 4 registered customers and then when you do the same thing on other browser like Opera or Microsoft Edge you have 5 registered customers.
Google Chrome Version 114.0.5735.134 (Official Build) (64-bit)
Opera Version:99.0.4788.65
Microsoft Edge Version 114.0.1823.51 (Official build) (64-bit)

**Steps to reproduce**
1. Go to https://www.globalsqa.com/angularJs-protractor/BankingProject/#/manager/list

**Expected result**

I should have the same number of customers on all of the browsers. 

**Actual result**

The number of customers varies depending on which browser I'm working

**Test data**


### =>Title: Overloaded balance
**Priority & severity**

P1 - HIGHT

**Description**

You can overload the balance account.

**Steps to reproduce**
1. Go to https://www.globalsqa.com/angularJs-protractor/BankingProject/#/login
2. Click on “Customer login” 
3. Select Harry Potter and click Log in
4. Click “Deposit”
5. Type 99999999999999999999999999999
6. Click on Deposit

**Expected result**

You should not be able to overload the balance.

**Actual result**

You can overload your balance.

**Test data**

Harry Potter
99999999999999999999999999999

### =>Title: Console error
**Priority & severity**

P6 - LOW

**Description**

When I press F12 an go to Console some warnings are shown.

**Steps to reproduce**
1. Go to https://www.globalsqa.com/angularJs-protractor/ConsumptionCalculator/
2. Press F12 and go to console
3. Refresh page

**Expected result**

You should not have warnings in console.

**Actual result**

We have 3 warnings in the console.

**Test data**


### =>Title: Icon that are not showing
**Priority & severity**

P5 - MEDIUM

**Description**

When you select 1 cup of coffee an icon appears and it should be a picture.

**Steps to reproduce**
1. Go to https://www.globalsqa.com/angularJs-protractor/ConsumptionCalculator/
2. Select 1 cups of coffee

**Expected result**

An image appears on the right corner.

**Actual result**

Instead of an image an icon its appearing.

**Test data**

1 cups of coffee

### =>Title: Buttons and texts are not visible on mobile interfaces
**Priority & Severity**

P1 - MEDIUM

**Description**

When the user try to use this site on the mobile interface all the texts and the buttons are too small and you cannot see anything.

**Steps to reproduce**
1. Go to https://www.globalsqa.com/angularJs-protractor/ConsumptionCalculator/
2. Press F12 and go to “Toggle device toolbar“

**Expected result**

The texts and buttons should be more visible so you can use the application on the phone too.

**Actual result**

The texts and the buttons are too small and you cannot see anything.

**Test data**


### =>Title: Modifying URL and redirected on other site
**Priority & severity**

P3 - MEDIUM

**Description**

If you are adding some keywords in URL and hit enter then you where redirected on other site.

**Steps to reproduce**
1. Go to https://www.globalsqa.com/angularJs-protractor/ConsumptionCalculator/
2. Add /fdgasdfsdgsd in URL https://www.globalsqa.com/angularJs-protractor/ConsumptionCalculator/fdgasdfsdgsd

**Expected result**

You should not be redirected on other sites.

**Actual result**

You where redirected on https://www.globalsqa.com.

**Test data**

/fdgasdfsdgsd

### =>Title: No cigarette image is too big
**Priority & severity**

P6 - MEDIUM

**Description**

The image with no cigarette is too big and it should be under the line.

**Steps to reproduce**
1. Go to https://www.globalsqa.com/angularJs-protractor/ConsumptionCalculator/
2. Add 3 cigarettes

**Expected result**

The image with no cigarette should not be that big.

**Actual result**

The image with no cigarette is too big.

**Test data**

I had “3“ cigarettes

### =>Title: Negative value of cigarette
**Priority & severity**

P2 - MEDIUM

**Description**

You can place an negative number of TAR.

**Steps to reproduce**
1. Go to https://www.globalsqa.com/angularJs-protractor/ConsumptionCalculator/
2. Add 1 cigarette
3. Modify tar with negative number “-10” mg

**Expected result**

You should be not able to place a negative number of TAR.

**Actual result**

You can replace thenumber of mg TAR with any negative number.

**Test data**

-10 mg of TAR

------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## 3. Bug report https://www.primariatechirghiol.ro/

### =>Title: Broken links error 404
**Priority & severity**

P3 - MEDIUM

**Description**

Wen I go to “Formulare“ I found 2 broken links.

**Steps to reproduce**
1. Go to https://www.primariatechirghiol.ro/
2. Click on “Formulare“
3. Click on “Arhitect sef“ and “Alte formulare“

**Expected result**

These 2 links should bring me to other page with the right info.

**Actual result**

These 2 links gave me 404 error.

**Test data**


### =>Title: Broken link error 404
**Priority & severity**

P3 - MEDIUM

**Description**

This link should bring me to a page from sgg.gov.ro not an 404 error.

**Steps to reproduce**
1. Go to https://www.primariatechirghiol.ro/
2. Scroll down to “Legea 544/2001”
3. Click on “Documente de interes public”
4. Click on https://sgg.gov.ro/new/guvernare-transparenta-deschisa-si-participativa-standardizare-armonizare-dialog-imbunatatit-cod-sipoca-35/

**Expected result**

That link should redirect me to this page: https://sgg.gov.ro/1/guvernare-transparenta-deschisa-si-participativa-standardizare-armonizare-dialog-imbunatatit-cod-sipoca-35/.

**Actual result**

The link give me an 404 error.

**Test data**


### =>Title: Broken links bad hosts
**Priority & severity**

P3 - MEDIUM

**Description**

These links bring me to a page with an error “This site can’t be reached”.

**Steps to reproduce**
1. Go to https://www.primariatechirghiol.ro/
2. Scroll down to “Info turism“
3. Click on “Cazare“
4. Click on “Pensiunea Marea Neagra“ and “Vila Bella”

**Expected result**

These links should bring me to “Pensiunea Marea Neagra“ and “Vila Bella“ sites.

**Actual result**

These links gave me an error “This site can’t be reached”.

**Test data**


### =>Title: Broken link error 404
**Priority & severity**

P3 - MEDIUM

**Description**

This link it should take me to a document regarding the purchase of fuel based on lots.

**Steps to reproduce**
1. Go to https://www.primariatechirghiol.ro
2. Click on “Achizitii“
3. Click on “Publicatii privind intentia de a achizitiona”
4. Click on “PUBLICATIE ACHIZITIE COMBUSTIBIL AUTO PE LOTURI”

**Expected result**

Should take me to a document regarding the purchase of fuel based on lots.

**Actual result**

It gave me error 404.

**Test data**


### =>Title: Console error
**Priority & severity**

P2 - MEDIUM

**Description**

When I hit F12 and go to console it gives to me some errors.

**Steps to reproduce**
1. Go to https://www.primariatechirghiol.ro/
2. Press F12
3. Go to Console

**Expected result**

I should not have these errors. The console should be clean.

**Actual result**

When I open the console I have many errors.

util.js:187 Uncaught Error: Bootstrap's JavaScript requires at least jQuery v1.9.1 but less than v4.0.0
    at Object.jQueryDetection (util.js:187:13)
    at util.js:192:6
    at bootstrap.min.js:6:200
    at bootstrap.min.js:6:246
POST https://www.primariatechirghiol.ro/wp-content/themes/portal/petitie_persoana_fizica.php 404 (Not Found)
base.js:7761     POST https://play.google.com/log?format=json&hasfast=true&authuser=0 401
base.js:7761     POST https://play.google.com/log?format=json&hasfast=true&authuser=0 401

**Test data**


### =>Title: Broken links on English version
**Priority & severity**

P3 - MEDIUM

**Description**

When I click on the English flag right next to “Informatii publice” it directs me into a page where all the links appear with an error called error 404. 

**Steps to reproduce**
1. Go to https://www.primariatechirghiol.ro/
2. Click on the English flag

**Expected result**

All the links should not give me 404 error.

**Actual result**

All the links give me error 404.

**Test data**


### =>Title: Buttons and texts on Phone interface
**Priority & severity**

P2 - HIGHT

**Description**

The buttons and texts are not visible properly on the phone’s interfaces.

**Steps to reproduce**
1. Go to www.primariatechirghiol.ro/
2. Press F12
3. Click on “Toggle device toolbar”

**Expected result**

The buttons and texts should be visible properly on the phone’s interfaces.

**Actual result**

The buttons and text are not visible properly.

**Test data**


### =>Title: Email functionality error
**Priority & severity**

P3 - MEDIUM

**Description**

When I go to the “Contact“ page an click on “(Trimitere mail catre Primaria Techirghiol)“ an error occurs and I am not redirected to sent them an email.

**Steps to reproduce**
1. Go to https://www.primariatechirghiol.ro/ 
2. Click on “Contact“
3. Click on (Trimitere mail catre Primaria Techirghiol)

**Expected result**

The user should be redirected to an email form.

**Actual result**

An error occurs and you are not able to sent an email.

**Test data**


### =>Title: Blank pages
**Priority & severity**

P2 - MEDIUM

**Description**

When I go to “MOL 2019-2021“ page there is two links that should show me something but when I click on them nothing is shown, there are missing information.

**Steps to reproduce**
1. Go to https://www.primariatechirghiol.ro/ 
2. Click on “MOL 2019-2021“ button
3. Click on “Statutul unitatii administrativ-teritoriale” or “Regulamente privind procedurile administrative”

**Expected result**

These two pages should give me some information.

**Actual result**

These two pages are blank and nothing is displayed there.

**Test data**


------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## 4. Bug report https://juice-shop.herokuapp.com/#/

### =>Title: Dollar sign missing
**Priority & severity**

P4 - MEDIUM

**Description**

The dollar sign from every product is missing and it’s shown as a strange sign.

**Steps to reproduce**
1. Go to https://juice-shop.herokuapp.com/#/

**Expected result**

All the products should have the dollar sign after price.

**Actual result**

All the products have a strange sign instead of dollar sign.

**Test data**


### =>Title: Photo missing
**Priority & severity**

P1 - MEDIUM

**Description**

When I go to Photo wall section from menu, a photo is not shown to me.

**Steps to reproduce**
1. Go to https://juice-shop.herokuapp.com/#/
2. Click on “Side menu” button
3. Click on “Photo Wall”

**Expected result**

All the photo from that page should be visible.

**Actual result**

An photo from that page its not visible.

**Test data**

email: elis.galut96@gmail.com
pass: Test123!

### =>Title: "About Us" crash
**Priority & severity**

P2 - LOW

**Description**

When I go to menu at “About us” page after a few seconds it will crush and give me the Error code: RESULT_CODE_HUNG.

**Steps to reproduce**
1. Go to https://juice-shop.herokuapp.com
2. Click on menu button
3. Click on About us

**Expected result**

This page “About us“ should not crash when I open it.

**Actual result**

This page are crashing after I hit the “About us” button after a few seconds.

**Test data**


### =>Title: "About Us" language
**Priority & severity**

P3 - LOW

**Description**

When I set the English version on the site and then I go to About Us, the text that is written there is not in English but in another language.

**Steps to reproduce**
1. Go to https://juice-shop.herokuapp.com/
2. Select the English language on right corner
3. Click on “Menu”
4. Click on “About Us”

**Expected result**

The text that is written there should be translated to English.

**Actual result**

The text is in other language.

**Test data**


### =>Title: Blank page / modify URL
**Priority & severity**

P5 - HARD

**Description**

When I modify the URL I got a blank page and I cant go back to shop.

**Steps to reproduce**
1. Go to https://juice-shop.herokuapp.com/fdgthhdsfsd/

**Expected result**

It should have given me a warning that the page does not exist and give me possibility to go back to the site.

**Actual result**

An blank page it shown to me and I cannot longer navigate through site. 

**Test data**

https://juice-shop.herokuapp.com/fdgthhdsfsd/

### =>Title: Already logged in when you enter the site
**Priority & severity**

P1 - HARD

**Description**

Browser Chrome Version 114.0.5735.199 (Official Build) (64-bit)
Browser Microsoft edge Version 114.0.1823.67 (Official build) (64-bit)
If you enter the site first time you are already logged in with unknown user data.

**Steps to reproduce**
1. Go to https://juice-shop.herokuapp.com/#/

**Expected result**

When you first time enter the site you should be logged off. 

**Actual result**

You are logged in with an unknown user when you visit the first time this site.

**Test Data**

https://juice-shop.herokuapp.com/#/

------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## 5. Bug report https://fieni.ro

### =>Title: Broken link error
**Priority & severity**

P4 - LOW

**Description**

When the user goes to the bottom of the page an click to “Guvernarea transparentra, deschisa si participativa” image it will redirect you to a blank page with an error.

**Steps to reproduce**
1. Go to https://fieni.ro
2. Scroll down to the bottom page
3. Click the image “Guvernarea transparentra, deschisa si participativa”

**Expected result**

It should redirect you to another page with information about “Guvernarea transparentra, deschisa si participativa”.

**Actual result**

It give you an error and you cannot longer access the site.

**Test data**


### =>Title: The text does not shown properly on Phone interface
**Priority & severity**

P2 - HARD

**Description**

If you scroll down to “INVITATIE DEPUNERE“ and “INREGISTARE COMERCIANTI/PRODUCATORI IN SISTEMUL DE GARANTIE-RETURNARE (SGR) PANA PE DATA DE 28 FEBRUARIE 2023” the both section are not visible properly on the phone interface, the text and the buttons from the left side are cropped.

**Steps to reproduce**
1. Go to https://fieni.ro/
2. Press F12
3. Click on “Toggle device toolbar” or press Ctrl+shift+m

**Expected result**

The text and the buttons should be visible on the phone interface.

**Actual result**

The text and the buttons are cropped left side on the phone interface.

**Test data**


### =>Title: Text error
**Priority & severity**

P4 - MEDIUM

**Description**

When you click on “Concursuri“ button it will bring you to a page and there is a missing character.

**Steps to reproduce**
1. Go to https://fieni.ro/
2. Scroll down and click on “Concursuri“

**Expected result**

It should have been written “Anul 2023“.

**Actual result**

Its written “Anul 202“

**Test data**


### =>Title: Text is not displayed correctly
**Priority & severity**

P3 - HARD

**Description**

When I go to the section named “PROIECT “GESTIONAREA PANDEMIEI GENERATĂ DE VIRUSUL SARS-COV-2 LA LICEUL AUREL RAINU DIN ORAȘ FIENI, JUD. DÂMBOVIȚA”“ there is a title that is not fully visible.

**Steps to reproduce**
1. Go to https://fieni.ro/ 
2. Scroll down at the section “PROIECT “GESTIONAREA PANDEMIEI GENERATĂ DE VIRUSUL SARS-COV-2 LA LICEUL AUREL RAINU DIN ORAȘ FIENI, JUD. DÂMBOVIȚA”“
3. Click on the “CIteste mai mult“ button

**Expected result**

The title should fit on entire rectangle.

**Actual result**

The title does not fit on that rectangle.

**Test Data**


### =>Title: Text is not displayed correctly
**Priority & severity**

P3 - HARD

**Description**

When I go to the section named “INVITATIE DEPUNERE OFERTE PENTRU  „CONTRACTAREA UNEI FINANȚĂRI RAMBURSABILE INTERNE PENTRU FINAȚAREA PROIECTULUI DE INVESTIȚII ”REABILITAREA, EXTINDEREA ȘI MODERNIZAREA ȘCOLII GIMNAZIALE DIACONU CORESI, ORAȘ FIENI, JUDEȚ DÂMBOVIȚA „“ there is a title that is not fully visible.

**Steps to reproduce**
1. Go to https://fieni.ro/
2. Scroll down at the section “INVITATIE DEPUNERE OFERTE PENTRU  „CONTRACTAREA UNEI FINANȚĂRI RAMBURSABILE INTERNE PENTRU FINAȚAREA PROIECTULUI DE INVESTIȚII ”REABILITAREA, EXTINDEREA ȘI MODERNIZAREA ȘCOLII GIMNAZIALE DIACONU CORESI, ORAȘ FIENI, JUDEȚ DÂMBOVIȚA „“
3. Click on the “CIteste mai mult“ button

**Expected result**

The title should fit on entire rectangle.

**Actual result**

The title does not fit on that rectangle.

**Test Data**


### =>Title: Text is not displayed correctly
**Priority & severity**

P3 - HARD

**Description**

When I go to the section named “INREGISTARE COMERCIANTI/PRODUCATORI IN SISTEMUL DE GARANTIE-RETURNARE (SGR) PANA PE DATA DE 28 FEBRUARIE 2023“ there is a title that is not fully visible.

**Steps to reproduce**
1. Go to https://fieni.ro/
2. Scroll down at the section “INREGISTARE COMERCIANTI/PRODUCATORI IN SISTEMUL DE GARANTIE-RETURNARE (SGR) PANA PE DATA DE 28 FEBRUARIE 2023“
3. Click on the “CIteste mai mult“ button

**Expected result**

The title should fit on entire rectangle.

**Actual result**

The title does not fit on that rectangle.

**Test Data**


### =>Title: Language issue
**Priority & severity**

P2 - MEDIUM

**Description**

When I go to https://fieni.regista.ro/#verificare-cereri and I change the language from Romanian to another language for example English, The page are not fully translated to that language.

**Steps to reproduce**
1. Go to https://fieni.ro/
2. Hover “Digitalizare“ and then click on “Verificare solicitari“
3. Go to right corner and change the language from Romanian to English

**Expected result**

The page should be entirely translated to English.

**Actual result**

The page is not fully translated into English.

**Test data**


### =>Title: Language issue
**Priority & severity**

P2 - MEDIUM

**Description**

When I go to https://fieni.regista.ro/formulare  and I change the language from Romanian to another language for example English, The page are not fully translated to that language.

**Steps to reproduce**
1. Go to https://fieni.ro/ 
2. Hover “Digitalizare“ and then click on “Formulare online“
3. Go to right corner and change the language from Romanian to English

**Expected result**

The page should be entirely translated to English.

**Actual result**

The page is not fully translated into English.

**Test data**


------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## 6. Bug report http://testingchallenges.thetestingmap.org/index.php

### =>Title: Number characters inside the text field
**Priority & severity**

P2 - HARD

**Description**

The user can introduce numbers after first letter in the First Name field.

**Steps to reproduce**
1. Go to http://testingchallenges.thetestingmap.org/index.php

**Expected result**

User should not be able to add numbers after first letter.

**Actual result**

User can add numbers after first letter.

**Test data**

D4mi4n0

### =>Title: Confirmation message with no characters in the "First Name" field
**Priority & severity**

P2 - HARD

**Description**

When a user has pressed the "Submit" button without completing anything in the "First name" field, he receives a confirmation message.

**Steps to reproduce**
1. Go to http://testingchallenges.thetestingmap.org/index.php 

**Expected result**

The user should not receive a confirmation message if he does not fill in the "First Name" field.

**Actual result**

The user receives a confirmation message after pressing the "Submit" button without completing the "First Name" field

**Test data**


### =>Title: Confirmation message with a space in the "First Name" field
**Priority & severity**

P2 - HARD

**Description**

When a user write a space in “First Name“ field and then press the “Submit“ button he receive an confirmation message.

**Steps to reproduce**
1. Go to http://testingchallenges.thetestingmap.org/index.php 

**Expected result**

The user should not receive a confirmation message if he write space in the “First Name“ field.

**Actual result**

The user get a confirmation message after he write space in the “First Name“ field.

**Test data**


### =>Title: Confirmation message with more than maximum value characters
**Priority & severity**

P2 - HARD

**Description**

The user receives a confirmation message after he write more than the maximum value of characters in the “First Name“ field.

**Steps to reproduce**
1. Go to http://testingchallenges.thetestingmap.org/index.php 

**Expected result**

The user should not be able to receive a confirmation message after he write more than the maximum value of characters.

**Actual result**

The user receive a confirmation message after he write more than the maximum value of characters.

**Test data**

asdfghjklpasdfghjklpasdfghjklpp

### =>Title: Confirmation message with space in the middle of characters
**Priority & severity**

P2 - HARD

**Description**

The user receives a confirmation message after he write a space between characters.

**Steps to reproduce**
1. Go to http://testingchallenges.thetestingmap.org/index.php 

**Expected result**

The user should not receive a confirmation message if he write a space between characters. 

**Actual result**

The user receive a confirmation message if he write a space between characters.

**Test data**

test test

### =>Title: Confirmation message with numbers instead of characters
**Priority & severity**

P2 - HARD

**Description**

The user receives a confirmation message even if he write numbers instead of characters. 

**Steps to reproduce**
1. Go to http://testingchallenges.thetestingmap.org/index.php 

**Expected result**

The user should  not receives the confirmation message after he write numbers instead of characters.

**Actual result**

The user receives the confirmation message after he write numbers instead of characters.

**Test data**

12345

### =>Title: Confirmation message with special characters 
**Priority & severity**

P2 - HARD

**Description**

The user receives a confirmation message even if he write special characters instead of alphabetical characters.

**Steps to reproduce**
1. Go to http://testingchallenges.thetestingmap.org/index.php 

**Expected result**

The user should not receive the confirmation message after he write special characters instead of alphabetical characters.

**Actual result**

The user receives the confirmation message after he write special characters instead of alphabetical characters.

**Test data**

!@#$%^

### =>Title: Confirmation message with non ASCII characters
**Priority & severity**

P2 - HARD

**Description**

The user receives a confirmation message even if he write non ASCII characters instead of alphabetical characters.

**Steps to reproduce**
1. Go to http://testingchallenges.thetestingmap.org/index.php  

**Expected result**

The user should not receive the confirmation message after he write non ASCII characters instead of alphabetical characters.

**Actual result**

The user receives the confirmation message after he write non ASCII characters instead of alphabetical characters.

**Test data**

¢£¤¥§©µ

### =>Title: Confirmation message with html tag
**Priority & severity**

P2 - HARD

**Description**

The user receives a confirmation message even if he write HTML tag instead of characters.

**Steps to reproduce**
1. Go to http://testingchallenges.thetestingmap.org/index.php  

**Expected result**

The user should not receive the confirmation message after he write HTML tag instead of characters.

**Actual result**

The user receives the confirmation message after he write HTML tag instead of characters.

**Test data**

<h 1>test< / h1> (without spaces between <>)
