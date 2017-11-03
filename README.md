# UniteJS Test Angular JavaScript

## UniteJS Operations

* node unitejs/cli/bin/unite configure --packageName=angular-javascript --title="Angular JavaScript" --profile=AngularJavaScript --outputDirectory=./app
* node unitejs/cli/bin/unite generate --type=class --name=MyClass --outputDirectory=./app
* node unitejs/cli/bin/unite generate --type=component --name=MyComponent --outputDirectory=./app
* node unitejs/cli/bin/unite generate --type=directive --name=Directive --outputDirectory=./app
* node unitejs/cli/bin/unite generate --type=enum --name=MyEnum --outputDirectory=./app
* node unitejs/cli/bin/unite generate --type=guard --name=MyGuard --outputDirectory=./app
* node unitejs/cli/bin/unite generate --type=module --name=MyModule --outputDirectory=./app
* node unitejs/cli/bin/unite generate --type=pipe --name=MyPipe --outputDirectory=./app
* node unitejs/cli/bin/unite generate --type=service --name=MyService --outputDirectory=./app
* node unitejs/cli/bin/unite platform --operation=add --platformName=Electron --outputDirectory=./app
* node unitejs/cli/bin/unite platform --operation=add --platformName=Docker --outputDirectory=./app

## Build Operations

* gulp build
* gulp theme-build
* gulp unit
* gulp e2e-install
* gulp e2e
* gulp platform-electron-dev
* gulp build --buildConfiguration=prod
* gulp e2e
* gulp platform-web-package --buildConfiguration=prod
* gulp platform-electron-package --buildConfiguration=prod
* gulp platform-docker-package --buildConfiguration=prod
