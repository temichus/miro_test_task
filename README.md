# miro_test_task
###Java Version 
8 Update 261 
###Builder 
Maven
###Requirements 
- junit 4.12
- selenium-chrome-driver 3.141.59
- selenium-support 3.141.59
- snakeyaml 1.21
- commons-io 2.6
- image-comparison 4.3.0

###Test runner 
Junit

###Tes case location
src/test/java/MiroTest::share_board_test

###Configuration
 - prepare test_config.yaml file with the following structure:
     
    `url: "https://miro.com/"` <br>
    `user1: {USER1}` <br>
    `password1: {PASSWORD1}` <br>
    `user2: {USER2}` <br>
    `password2: {PASSWORD2}` <br>
    
    for example config already has credentials for test accounts, but it may be already outdated
 - put chromedriver bin that supported buy you chrome browser, buy project contains bin for chrome version 85.0.4183.121  