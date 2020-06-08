## how to run the backend server
1. need to create a **.env** file under the root directory to run the server. Need to include in the file: 
   * NODE_DEV:(development/production)
   * FRONTEND_ADDRESS
   * DB_ADDRESS
   * DB_USER
   * DB_PASSWORD
   * DB_NAME
   * SECRET
2. Before first run of the server, make sure mysql is added to your environment variable list and execute the following command: 
   * ./scripts/setup.sh
3. run the app under the project root directory: 
   * npm start

## issues
1. When using react-native init, cocoapads cannot be installed
<!-- 
### workarounds
1. If `react-native run-android` failed initial run:
  1. go to `[project folder]\android\gradle\wrapper\gradle-wrapper.properties` and change `distributionUrl` to `//services.gradle.org/distributions/gradle-6.3-all.zip` 
  2. go to `[project folder]\android` and run `./gradlew` -->