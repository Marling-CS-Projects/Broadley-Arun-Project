---
coverY: 0
---

# 2.2.1 Cycle 1 : Frontend Setup

## Design



in this project I have chosen to utilize angular JS which is an online, open-source JavaScript framework that is easier to use when creating complex applications. Angular JS allows me to increase the functionalities of HTML, allowing the creation of interactive web applications rather than just static sites.

The objective of this cycle was to Install the required dependencies on my development PC and to then build a basic Frontend app using the google's "material design" UI components.&#x20;

Objectives for the cycle are described below:

### Objectives

* [x] Install required dependencies
* [x] Create the basic angular FrontEnd application
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

###

###

###

### Outcome

At the end of my first Cycle I've managed to complete all my required objectives. What I've not done, though, is made the components look nice. To do that I will have to use CSS to define how each of the components should look. I will leave that for another Cycle.



### Challenges

Whilst I have used angular before in my EPQ, I had never tried to use the Material Design components within a front end application. It took me quite a while to understand how to implement the components I used and get them to do something even quite basic.

## Testing



### Tests

| Test | Instructions                                               | What I expect                                                                | What actually happens | Pass/Fail |
| ---- | ---------------------------------------------------------- | ---------------------------------------------------------------------------- | --------------------- | --------- |
| 1    | Run app                                                    | Web page to turn up                                                          | As expected           | Pass      |
| 2    | Select Auto complete component - type 'LL'                 | Dropdown field should only show options that contain 'LL' in text somewhere. | As expected           | Pass      |
| 3    | Select different Tabs 'Information', 'History', 'Analysis' | Frontend displays the correct web part.                                      | As expected.          |           |
| 4    | Move to 'History' tab.                                     | Check that grid is shown with one default record                             | As expected           |           |

### Evidence

1. **Website**&#x20;

**Initial view showing history table.**

![](<../../.gitbook/assets/image (5).png>)



2. **Main App Component Code and HTML**

<img src="../../.gitbook/assets/image (6).png" alt="" data-size="original">![](<../../.gitbook/assets/image (7).png>)

3. History Component Code and HTML

![](<../../.gitbook/assets/image (8).png>)![](<../../.gitbook/assets/image (9).png>)
