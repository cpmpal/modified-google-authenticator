# Modified google authenticator

Added an ability to change the amount of digits sent to the TOTP generator which has the ability to do so natively. Adds a slider on the import secret key screen to specify the digits and saves that info with each key stored in the sqlite table. Allows google authenticator to work for something like battle.net authentication as it can display the proper 8 digits for authentication instead of the default 6, if the secret key is known for the account
