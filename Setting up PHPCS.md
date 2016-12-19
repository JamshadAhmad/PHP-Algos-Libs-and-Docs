##Setting up PHPCS (CodeSniffer) in PhpStorm

###1) Install

`sudo pear install PHP_CodeSniffer`

or

`sudo apt install php-codesniffer`

it should be at /usr/bin/phpcs , make it sure by running

`which phpcs`


###2) Configure 
PHPStorm-> File -> Settings -> Search [sniffer]

Click on "Code Sniffer", 
select configuration "By default project interpreter"


###3) Enable 
Again in same search result
Click on Editor > Inspections

Click (on right) PHP > "PHP Code Sniffer Validations"

On the further right, press Reload icon on Coding Standard.
Select PSR2. Apply and Ok.

You're good to go, phpcs warnings will be displayed in your PHP files.
