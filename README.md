# The Desktop GUI Application for the Salesforce Data Loader SFDX Plugin (SFDMU)

- #### The plugin repository:   [https://github.com/forcedotcom/SFDX-Data-Move-Utility](https://github.com/forcedotcom/SFDX-Data-Move-Utility)
- ##### For the detailed documentation, visit the project Wiki: [https://github.com/forcedotcom/SFDX-Data-Move-Utility/wiki)
- ##### Download also the SFDMU Desktop GUI Application: [https://github.com/forcedotcom/SFDX-Data-Move-Utility-Desktop-App)

----

**The advanced Salesforce Data Loader SFDX Plugin (SFDMU) will assist you to populate your org (scratch/development/sandbox/production) with data imported from another org or CSV files. Supports Delete, Insert, Update and Upsert for multiple related sObjects.** 

----
**This repository contains the <u>special Desktop Application</u> allows you to manage SFDMU plugin configuration files <u>from the simple and intuitive UI</u>.**

----



### When can this Application be very useful ?

Apart from the minimal setup the export.json file has a lot of advanced properties that can be leveraged in creating and running complex migration jobs.

Therefore in some cases the json file may become very long and hard to edit it manually using the standard Notepad. 

Now with this Desktop Application you don't have to work with the Notepad and the Console, because all actions are performed in a visual mode. Now it's very simple to manage the migration jobs. You can add and remove org connections, set up SObjects and fields, then run the Plugin from the application itself. 



### Installation and running.
```bash
# 1. Install the SFDMU Plugin from: https://github.com/forcedotcom/SFDX-Data-Move-Utility

# 2. Clone this repository.
git clone https://github.com/forcedotcom/SFDX-Data-Move-Utility-Desktop-App.git

# 3. Go into the project directory.
cd SFDX-Data-Move-Utility-Desktop-App

# 4. Install Python
https://www.python.org/downloads/release/python-2717/

# 5. Install yarn
https://classic.yarnpkg.com/en/docs/install

# 6. Install node-gyp globally
yarn global add node-gyp

# 7. Install electron globally
yarn global add electron

# 8. Install electron into app directory
yarn add electron

# 9. Install other dependencies
npm install

# 10. Compile.
npm run build

# 11. Run.
npm run main
```



## Notes

* This Application must have the [SFDMU Plugin](https://github.com/forcedotcom/SFDX-Data-Move-Utility) to be installed in your system previously.
  
* The Application puts its configuration & data files into the standard user's Documents path inside dedicated directory named **/SFDMU**.
  
* The Application supports multiple local users. 
  Each user has his own local profile contains all his data, that is encrypted by the encryption key which is the password that is used to login into the application. 
  So user's data never directly exposed to others. But after the creating of your local user's profile, you need to well remember your password because there is no password recovery option.

* Supported all major hosts (Win, MACOS, Linux)



## License

This product is licensed under the BSD-3-Clause - see the [LICENSE.txt](LICENSE.txt) file for details.




