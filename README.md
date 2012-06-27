# GOOGLE KEYWORDS MODULE FOR FUEL CMS
This is a [FUEL CMS](http://www.getfuelcms.com) google_keywords module for adding google_keywords like functionality including posts, categories, and commenting.

## INSTALLATION
There are a couple ways to install the module. If you are using GIT you can use the following method
to create a submodule:

### USING GIT
1. Open up a Terminal window, "cd" to your FUEL CMS installation then type type in: 
Type in:
``php index.php fuel/installer/add_git_submodule git://github.com/daylightstudio/FUEL-CMS-Google-Keywords-Module.git google_keywords``

2. Then to install, type in:
``php index.php fuel/installer/install google_keywords``


### MANUAL
1. Download the zip file from GitHub:
[https://github.com/daylightstudio/FUEL-CMS-Google-Keywords-Module](https://github.com/daylightstudio/FUEL-CMS-google_keywords-Module)

2. Create a "google_keywords" folder in fuel/modules/ and place the contents of the google_keywords module folder in there.

3. Then to install, open up a Terminal window, "cd" to your FUEL CMS installation then type type in:
``php index.php fuel/installer/install google_keywords``

## UNINSTALL

To uninstall the module which will remove any permissions and database information:
``php index.php fuel/installer/uninstall google_keywords``

### TROUBLESHOOTING
1. You may need to put in your full path to the "php" interpreter when using the terminal.
2. You must have access to an internet connection to install using GIT.


## DOCUMENTATION
To access the documentation, you can visit it [here](http://www.getfuelcms.com/user_guide/modules/google_keywords).

## TEAM
* David McReynolds, Daylight Studio, Main Developer

## BUGS
To file a bug report, go to the [issues](https://github.com/daylightstudio/FUEL-CMS-Google-Keywords-Module/issues) page.

## LICENSE
The google_keywords Module for FUEL CMS is licensed under [APACHE 2](http://www.apache.org/licenses/LICENSE-2.0).