# MSailing-DirectoryRemove
This python script will remove a list of uniqnames from the Sailing Recruits group on MCommunity.

## Installation

1. Clone this repository to your local machine.

2. Make sure you have python installed. You will also need Selenium, a module for python. In terminal run:

	`sudo -H pip install selenium`

3. You need to have Google Chrome installed for this to work. If you are on a Mac, the included chromedriver should work. Otherwise replace `chromedriver` with the correct version from [here](https://sites.google.com/a/chromium.org/chromedriver/).

4. Open `directory_remove.py` and enter your Umich username and password where it says `ENTER_USERNAME_HERE` and `ENTER_PASSWORD_HERE`.


## Usage

For any number of uniqnames:

`python directory_remove.py uniqname1 uniqname2`