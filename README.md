### Insta-Login Bot

#### Description
Hepls in Login Automation through selenium using javascript in linux.

#### SetUp 
**Step-1** Install Node
> $ sudo apt install nodejs

**Step-2** Once node installed check the version
> $ node -v 

**Step-3** Download npm(node package manager)
> $ sudo apt install npm

**Step-4** Download selenium webdriver
> $ npm install selenium-webdriver

**Step-5** According to your preference of  browser you can download its webdriver.
(make sure before downloading the webdriver you have the corresponding browser installed)
(here i am using chromium webdriver )
you can download it from the given link:-
https://chromedriver.chromium.org/downloads
 
you will get a zip file extract in on the desired location
**Step-6** Setting up the enviromental variable so that you can access the webdriver from anywhere .
> $ vim .bashrc

- it will open the vim text editor
setup the path as:
> $ export PATH=$PATH: /path/to/your/extracted webdriver
#### system is ready


#### Getting started with selenium
**Step-1** create a folder
open terminal move to that folder
**Step-2** initizalising
> $ npm init -y

**Step-3** installing required selenium-webdriver
> $ npm install selenium-webdriver

it will create the required packages and modules
**Step-4** make a js file
now you are ready for further assistance prefer the documentation
https://www.selenium.dev/documentation/en/getting_started/
**Step-5** once the js file is saved 
> $ node filename
to start the script






