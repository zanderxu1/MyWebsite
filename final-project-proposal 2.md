# Crime Alarm

 * Name: Xinhe Xu(xinhexu2), Zhenzhou Yang(zy29) | Moderator: Jack Gentile (jtg2)

# Abstract
* Project Motivation:
  * Since there is one PhD student at Chicago that has been shot and lost his life. We want to create an App that everyone can check if the places they are visiting are safe enough from their mobile phones.
 
* Project Purpose:
  * The App can show the crime information, the potential risk of the area. Also can search for specific area and point out some dangerous areas. 



# Technical Specification:

  * API: https://data.cityofchicago.org/resource/x2n5-8w5q.json
  * Programming Language:Python, JavaScript, HTML
  * IDE: Visual Studio Code/Pycharm/Android Studio
  * Tools/Interface: React Native, React Navigation, Android emulator (Android Studio)
  * Style conventions: JavaScript Style Guide
  * platform: cross-platform app


# Functional Specification:
  
  * Main Page:

    1. Splitting the city into several sections and for each section we will show the number of crimes happened in this area on the map
    2. Use the different color to show the area’s potential risk

  * Crime data list page:

    1. Show all the Crime data as a list just including the name and location and date.
    2. Can use a range of date to search the crime data
    3. We can change the location in Crime data page
    4. Tap on the specified crime can show its concrete information
    5. Click on the specific data, it can go to the crime information page
    6. Show the highlight of the crime which has not been resolved

  * Crime Information Page:

    1. It can show the details of specific crime data.
    2. Show the highlight of the crime which has not been resolved

  * Visualization page:

    1. Show the Crime risk rank
    2. Show the number of crime in Chicago area
    3. Show the each type of crime number 

# Brief Timeline:
  
  * Week1:
    1. Get the data from Chicago Crime 
    2. Clean and parse the data, extract the information we need 
    3. Design the UI for the pages

  * Week2:
    1. Implement the main page to show the splited areas on the map
    2. Create the draft of list and information page

  * Week3:
    1. Improve the mainpage
    2. Finish the list page and information page

  * Week4:
    1. Fix the bugs and improve the application
    2. Implement the visualization page(Show the total number of crime in Chicago and show the each type of crime number)
    3. Do the data visualization: Rank of risk level for the areas

# Division of Labor:	

* Zhenzhou Yang: 
  * List page and information page, data, unit test and manual test, Visualization page: number of crime

* Xinhe(Zander) Xu:
  * Main Page, Map, List page:highlight crimes, list data, data, unit test and manual test, Visualization page: Rank of risk and the each type of crime number, navigation

# Rubrics for Zhenzhou:

* Week1:

| Category | Total Score Allocated | Detailed Rubrics |
| ------------- |:-------------:| -----:|
| Connect the api successfully | 5 | +0 If we cannot get correct data <br>+2 If we can get the correct data from the api<br>+3 Store the data in a file(local store the data |
| Data Cleaning check, parse the data | 4 | -1 for each kind of the required data that cannot be parsed <br> +4 All of the required data can be parsed correctly|
| Design the list/info/visualization pages | 6 | +0 If do not include the design of the pages<br>+2 For each design of the pages |
| Unit test | 6 | +1 per unit test |
| Manual Test: Design main page | 4 | +4 Show the main page design |
* Link: 

* Week2:

| Category | Total Score Allocated | Detailed Rubrics |
| ------------- |:-------------:| -----:|
| Filter the latest crime data within several months | 5 | +0 If we cannot get correct time data <br>+5 Get the correct time period data|
| Implement the list page | 5 | +3 Page can show the list of crimes <br> +2 Each crime can be clicked to jump into its information page |
| Implement the information page | 5 | +2 Page can show all of the specific info for the current crime <br>+2 Can move back to the list page <br>+1 Can navigate to main page directly from info page|
| Unit test | 5 | +1 per unit test |
| Manual Test| 5 | +3 Manual test plan include the list page <br> +2 Manual test plan include the info page|
* Link: 
* Week3:

| Category | Total Score Allocated | Detailed Rubrics |
| ------------- |:-------------:| -----:|
| Add the filter buttons and drop list | 5 | +2 Add the filter section correctly in the list page <br> +2 Can list some options for users to choose as filter <br> +1 Finish the filter section with reasonable design and UI|
| Implement the search and filter function in list page | 5 | +4 Can read and combine the filter requirements specified by user to filter the correct data <br> +1 Can update the page with filtered data|
| Highlight the crimes with different style based on our risk rule | 5 | +4 Style the different crimes <br> +1 The result has a good UI design|
| Manual Test | 10 | +4 show the screenshot of the correct highlight the crimes with high risk <br> +3 Show the screenshot of the crime data list in list page<br>+3  Finish the other parts of week3's manual test plan|
* Link: 
  
* Week4:

| Category | Total Score Allocated | Detailed Rubrics |
| ------------- |:-------------:| -----:|
| Improve and fix the bugs for former weeks | 5 | -1 for each bug found in list and info page <br> +5 both pages can be interacted smoothly and run without error |
| Show each type of crime number in Chicago | 5 | +3 show the number correctlt <br> +2 set the postion of this part in a good format|
| Manual Test | 10 | +4 Show the rank correctly in manual test plan <br> +3 Show the number for each crime correctly in the manual test plan <br>+3  Show other parts of the manual test plan in week 4|
* Link: 

# Rubrics for Xinhe:

* Week1:

| Category | Total Score Allocated | Detailed Rubrics |
| ------------- |:-------------:| -----:|
| Connect the api successfully | 5 | +0 If we cannot get correct data <br>+2 If we can get the correct data from the api<br>+3 Store the data in a file(local store the data |
| Data Cleaning check, parse the data | 5 | +1 for per different kinds of data parse correctly |
| Design the main pages | 5 | +0 If do not include the design of main pages<br>+2 If including basic features of the main page in pdf<br>+1 add per new features of main pages|
| Unit test | 6 | +1 per unit test |
| Manual Test: Design main page | 4 | +4 Show the main page design |
* Link: https://docs.google.com/spreadsheets/d/1nlbT1gS16b9EnX6OXRtmiM263vJ3xGddc8hOXppxZ60/edit#gid=0

* Week2:

| Category | Total Score Allocated | Detailed Rubrics |
| ------------- |:-------------:| -----:|
| divide the area of data and count the number| 5 | +0 If we cannot get correct solving data <br>+3 divide the data correctly and reasonable <br> count the each area's crime number|
| Implement the main page | 5 | +2 Show the map on the main page <br> +2 Include the circle which can navigate from main page to list page|
| Add the navigation between different pages| 5 | +2 Can move from main page to list page<br>+2 Can move from list page back to main page<br>+1 Can move from information page to visualization page|
| Unit test | 5 | +1 per unit test |
| Manual Test| 5 | +3 Manual test plan include the map in main page <br> +2 Manual test plan include the navigate button|
* Link: https://docs.google.com/spreadsheets/d/1_akeWP9gEJdn34aaYo9rKIPGzRzgRRlaa8dv_ueM_L8/edit#gid=0

* Week3:

| Category | Total Score Allocated | Detailed Rubrics |
| ------------- |:-------------:| -----:|
| Set the list page UI, which can present the Crime data as a list | 5 | +3 If the list page show the crime data<br>+2 If the list page show the crime data in a good position design|
| Set the navigation between the specific crime data to it's information page | 5 | +3 Set the navigation<br>+2 Navigation works for each data|
| Improve the main page | 5 | + 3 show the crime number in each area on each area circle <br>+2 show the different color of circle according to the crime number|
| Manual Test | 10 | +4 show main page improvement in manual test plan <br> +3 Show the screenshot of the crime data list in list page<br>+3  Finish the other parts of week3's manual test plan|
* Link: https://docs.google.com/spreadsheets/d/1vPXcErU9vcY4JGfN6J2ZVGm7spvNBR_C5wyqvfHYKes/edit#gid=0
  
* Week4:

| Category | Total Score Allocated | Detailed Rubrics |
| ------------- |:-------------:| -----:|
| Rule the crime risk| 5 | +1 add per condition and successful filt the data|
| Improve the usage of the application | 5 | +2 For per improvement in main page or list page or information page <br> +1 for per improvement in visualization page|
| Show each type of crime number in Chicago | 5 | +2 show the data correctlt<br> +2 show the data as a list with crime type name and number<br> +1 show this part with a good design|
|Unit Test|4|+1 For per unit test for rule the crime risk|
| Manual Test | 6 | +2 Show the rank correctly in manual test plan <br> +2 Show the number for each crime correctly in the manual test plan <br>+2  Show other parts of the manual test plan in week 4|
* Link: https://docs.google.com/spreadsheets/d/1bZ3Mmm7rRnUJHMgQnLTADtMqyPs4f3WbzqktQllYnPk/edit#gid=0
  
# Figures:
* Including all of the page views, buttons and so on.