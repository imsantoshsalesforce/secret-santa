# secret-santa
Created a fun application for the eve of Christmas and New Year celebration where user can given option to choose any gift from the basket. The secret santa will gift you some thing amazing gift with important message


## Creating LWC OSS App

npx create-lwc-app Enter app name

Install SLDS npm i @salesforce-ux/design-system npm i @lwc/synthetic-shadow

Add below line in lwc-services.config.js       
{ from: 'node_modules/@salesforce-ux/design-system/assets', to: 'dist/SLDS' }

Add below line in index.html    
    link rel="stylesheet" type="text/css" href="./SLDS/styles/salesforce-lightning-design-system.css"

Add below line in index.js    
import '@lwc/synthetic-shadow';

npm run build

npm run watch
