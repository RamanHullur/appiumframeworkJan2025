#Road Map for Framework Design:


Installation Steps:

homebrew Installation Via cmd or pkg
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"

brew --version
brew install node
node -v
npm -v

npm install -g appium@next or  sudo npm install -g appium@nex
appium -v

npm install -g appium-doctor or sudo npm install -g appium-doctor
appium-doctor

xcode-select --install or from Xcode 
xcrun simctl list devices or Xcode IDE

brew install carthage
carthage version

echo $JAVA_HOME
echo $ANDROID_HOME


brew install ideviceinstaller libimobiledevice ios-deploy
ideviceinstaller -v  
ios-deploy --version
libimobiledevice -v

https://inspector.appiumpro.com

 
If driver has rpm installation issue: Encountered an error when installing package: npm command 'install --save-dev --no-progress --no-audit --omit=peer --save-exact --global-style --no-package-lock appium-uiautomator2-driver --json' failed with code 1.


sudo chown -R 501:20 "/Users/apple/.npm" 
ls -l /Users/apple/.npm 

appium driver install uiautomator2
appium driver install xcuitest

npm install --save-dev appium-uiautomator2-driver
npm list --depth=0 

appium driver list  
Listing available drivers
- xcuitest@7.35.1 [installed (npm)]
- uiautomator2@3.9.9 [installed (npm)]
- mac2 [not installed]
- espresso [not installed]
- safari [not installed]
- gecko [not installed]
- chromium [not installed]


https://www.npmjs.com/package/@appium/images-plugin 

appium plugin list 
- images [not installed]
- wait [not installed]
- execute-driver [not installed]
- relaxed-caps [not installed]
- universal-xml [not installed]

How to use plugin:
appium --use-plugins=images
 appium plugin install --source=npm appium-wait-plugin
appium plugin install images
 npm install -g appium-images 
npm install -g appium-execute-driver 
npm install -g appium-relaxed-caps 
npm install -g appium-universal-xml 
https://inspector.appiumpro.com


