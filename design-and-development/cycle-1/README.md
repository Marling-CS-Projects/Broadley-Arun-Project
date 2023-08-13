---
coverY: 0
---

# 2.2.1 Cycle 1 : Frontend Setup

## Design



in this project I have chosen to utilize angular JS which is an online, open-source library used for JavaScript framework that is easy to learn and has many unique features. angular JS allows me to increase the functionalities of HTML, allowing the creation of interactive web applications rather than just static sites.

The objective of this cycle was to Install the required dependencies on my development PC and to then build a basic frontend app using the google's "material design" UI components.&#x20;

Objectives for the cycle are described below:

### Objectives

* [x] Install required dependencies
* [x] Create the basic angular frontend application
* [x] Create the 4 initial web parts  Header, Info,  History and the Analysis Component
* [x] Install the Material Design UI Components.
* [x] Use some of those UI Components in the FrontEnd.

### Key Angular Pages&#x20;

Each Angular Application is built up of a number of web page components which then can be assembled to produce the website. For this initial design of the website I've created 4 stub web page components, described below.



<table><thead><tr><th width="223">Webpage Component</th><th>Use</th></tr></thead><tbody><tr><td>Header </td><td>The header component contains the title of the web-page, a Stock Selector component and a Button 'Get Info' which will eventually retrieve data for the selected stock from the back-end.</td></tr><tr><td>Information</td><td>Currently only in Stub form, this page will show information about the selected stock from the back-end of the system.</td></tr><tr><td>History</td><td>This component will show history of share price movements for the stock. Will be implemented using a Table Grid.</td></tr><tr><td>Analysis Component</td><td>This will show the results of the analysis.</td></tr></tbody></table>

### Code to setup Application

Basic setup of the application was done using a cmd line script.

````
create.bat
ng new PredictorFE   // Create new angular application
cd PredictorFE 
ng g c header  //  create the header web part.
ng g c analysis  // create the analysis web part.
ng g c info      // create the info web part.
ng g c history   // create the history web part.
```
````

## Material Design Components



| Different componenents | Explanation of use                                                                                                                                                                                                                                                                                  | Image                                                            |
| ---------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------- |
| Table                  | I am using a "table" component which is used in my website to display different information like "stock growth" and "history" in a clear way.                                                                                                                                                       | ![](broken-reference)![](<../../.gitbook/assets/image (10).png>) |
| Button                 | I am using a "button" component which is used in my website to perform actions like "get info" which displays information about a given stock.                                                                                                                                                      | ![](<../../.gitbook/assets/image (1) (1).png>)                   |
| Tab                    | I am using a "tab" component which is used on my website to allow the user to open different blocks of information on the same table. This information includes a "history" tab that shows historical data of a given stock and "analysis" which shows linear regression analysis of a given stock. | ![](<../../.gitbook/assets/image (5).png>)                       |
| Autocomplete           | I am using an "autocomplete" component which is used on my website in a section where you choose a stock to analyse. The autocomplete component displays all the stock options following the letters you type making it a lot easier to select the stock you want.                                  | ![](<../../.gitbook/assets/image (2) (1).png>)                   |



### Outcome

At the end of my first Cycle I've managed to complete all my required objectives. What I've not done, though, is made the components look nice. To do that I will have to use CSS to define how each of the components should look. I will leave that for another Cycle.



### Challenges

Whilst I have used angular before in my EPQ, I had never tried to use the Material Design components within a front end application. It took me quite a while to understand how to implement the components I used and get them to do something even quite basic.

## Testing

Evidence for testing

### Tests

<table><thead><tr><th width="85">Test</th><th>Instructions</th><th>What I expect</th><th>What actually happens</th><th>Pass/Fail</th></tr></thead><tbody><tr><td>1</td><td>Run app</td><td>Thing happens</td><td>As expected</td><td>Pass</td></tr><tr><td>2</td><td>Select Auto complete component - type 'LL'</td><td>Something happens</td><td>As expected</td><td>Pass</td></tr><tr><td>3</td><td>Select different Tabs 'Information', 'History', 'Analysis'</td><td>Front-end displays the correct web pars when tab is selected</td><td>As expected</td><td>Pass</td></tr><tr><td>4</td><td>Move to 'History' tab</td><td>Check that the table grid is shown with one default record.</td><td>As expected</td><td>Pass</td></tr></tbody></table>

### Evidence

#### Initial Website Setup

![](../../.gitbook/assets/image.png)

#### Main App component Code and HTML.

![](<../../.gitbook/assets/image (1).png>)![](<../../.gitbook/assets/image (2).png>)



#### History Component Code & HTML

![](<../../.gitbook/assets/image (3).png>)![](<../../.gitbook/assets/image (4).png>)
