# Auto Lightroom Trial Reset
This is a small compilation of scripts to automatically reset your Lightroom CC trial. Giving you unlimited free use. This works with all Lightroom CC version prior to Lightroom CC 2019. This is meant for educational purposes, please support developers if you like their products.


# How it works
AutoLightroomTrialResetter composes of a few different scripts and files. The main script simply edits the application.xml file found in /Library/Application Support/Adobe/Lightroom CC AMT/AMT/ increasing the trial serial number with one. This causes lightroom to reset your 7 day trial. Then there is a plist file that is imported to LaunchDaemons that allow MacOs to automatically execute the main script every 7 days. Lastly there is the installation script which simply copies all the necessary files to the correct folders and loads the plist into launchctl. Your password is required to do this as files are copied to system folders, however this is completely safe and the installer does not save your password.


# How to use
Simply run the installer with terminal, enter your password (you need to be system administrator) and then you should be done. Just check the terminal window to ensure that there weren’t any errors.
