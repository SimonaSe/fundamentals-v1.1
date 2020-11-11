
# Module 5 - Introduction to Tracker (3 hr)

## 5.0 Overview of the module (5 min)

### What is in this module

So far, you have seen how DHIS2 can be used for the reporting, analysis and dissemination of data (module 2); for data analysis using pivot tables, charts and maps (module 3); and have also seen how DHIS2 can be customized to meet the needs of a particular country or organization (module 4).

In Module 5, you will learn how data from real patients are entered into DHIS2 using two applications: Event capture and Tracker capture.

By watching these demonstrations, you will see how to capture data excluding personal information, but still collected at the individual level, by reviewing the Event model in DHIS2. You will also learn how individual, personal information is collected using the Tracker model in DHIS2. You will also learn how to analyze this data using the analysis tools that you are already familiar with. Like in the previous modules, you will be prompted to perform some exercises using Trainingland following the steps shown in the videos.

At the end of subsection 5.4 you will find a graded assignment divided into 3 steps. This graded assignment contributes 8% of your final grade. After these assignments have been completed, you will find the last graded quiz of the course which counts towards 5% of your final grade. This module is therefore responsible for 13% of your overall grade between the assignment and quiz.

We estimate that you will take about 3 - 4 hours to view all the videos and complete both ungraded and graded learning activities. This will vary slightly for each learner but should give you a good indication of the time required to complete this module.

## 5.1 - Tracker Introduction Presentation

### Video - Tracker Intro Presentation (5 min)

So far, we have been dealing with reviewing the concepts related to the collection, analysis and dissemination of aggregate data. Source data and patient level information is often not collected this way however, and the need for more transactional, individual-based data collection and analysis mechanisms makes itself readily apparent within a variety of sectors.

That’s the purpose of DHIS2 Tracker, which is divided into 2 main models: **Event**and **Tracker**. In this video, we will provide a brief background on this Tracker concept as well as contrast the Event and Tracker models as it relates to collecting individual data.

[https://www.youtube.com/watch?v=-3Os3E6EMEU](https://www.youtube.com/watch?v=-3Os3E6EMEU)

## 5.2 - Event Programs

### Video - Introduction to Event Programs and Event Capture (5 min)

Event Programs allow you to collect data about a specific and isolated event that will later feed aggregated data models into DHIS2. Information on event programs is collected via the Event Capture app. In this video, we will discuss event programs and the event capture app, utilizing real life use cases to demonstrate where event programs can be practical to use in practice.

[https://www.youtube.com/watch?v=Nqxee03vqTs](https://www.youtube.com/watch?v=Nqxee03vqTs)

More information on the SARA survey: <https://www.who.int/healthinfo/systems/sara_indicators_questionnaire/en/>

### Video - Event Capture Demo - Part 1 of 4 (10 min)

Now that you understand the purpose of the Event Capture app, let’s see how it works within DHIS2.

In this video, you will review the **Event Capture interface**, understand how collected data is displayed within the app and learn how to filter and edit entered data for specific programs.

[https://www.youtube.com/watch?v=-IojjGyrURU](https://www.youtube.com/watch?v=-IojjGyrURU)

#### Activity 1 - Introducing the event capture interface

Please do this activity in [TRAININGLAND](https://live.academy.dhis2.org/tl1/dhis-web-commons/security/login.action).

* Familiarize yourself with the event capture interface.
* Navigate to event capture by selecting Apps -> Event Capture.

<p id="gdcalert183" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image183.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert184">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>

![alt_text](images/image183.png "image_tooltip")

* Select any of the organisation units at the facility level within Trainingland.

<p id="gdcalert184" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image184.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert185">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>

![alt_text](images/image184.png "image_tooltip")

* Select Malaria case management as the program. Note that you do not select a period; this differs from the aggregate data entry app in which a period must be selected before any data appears.

<p id="gdcalert185" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image185.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert186">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>

![alt_text](images/image185.png "image_tooltip")

After selecting a program, the related events will appear.

<p id="gdcalert186" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image186.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert187">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>

![alt_text](images/image186.png "image_tooltip")

You can try the following functionality to see how it works:

* Print List: Prints the list of events that is displayed on the page you are viewing within the event capture app. Click on the "Print list" button in order to view the output.

<p id="gdcalert187" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image187.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert188">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>

![alt_text](images/image187.png "image_tooltip")

* Download events: This will download the events that are displayed in event capture in one of XML, JSON or CSV file formats directly to your computer.

<p id="gdcalert188" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image188.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert189">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>

![alt_text](images/image188.png "image_tooltip")

* Show/hide columns: This will add additional columns to the event capture front page. These columns in event capture represent the data elements which are associated with the program you have selected. You can access this using the "Show/hide columns" button.

<p id="gdcalert189" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image189.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert190">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>

![alt_text](images/image189.png "image_tooltip")

If you left-click on an event, some options will appear. The event will only have an audit history if it has been changed. You can try to select some of the options to see the effect they have on the event.

<p id="gdcalert190" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image190.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert191">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>

![alt_text](images/image190.png "image_tooltip")

### Video - Event Capture Demo - Part 2 of 4 (10 min)

In this video, you’ll see the step-by-step process required to **register a new event** in the Event capture app and how **data validation** can be incorporated when working with this type of data

[https://www.youtube.com/watch?v=THD3a6UJN9A](https://www.youtube.com/watch?v=THD3a6UJN9A)

#### Activity 2 - Register a new event

Please do this activity in [TRAININGLAND](https://live.academy.dhis2.org/tl1/dhis-web-commons/security/login.action).

* Select any of organisation units at the facility level within Trainingland and select the SARA RCH program.

<p id="gdcalert191" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image191.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert192">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>

![alt_text](images/image191.png "image_tooltip")

* Left-click "Register event" to create a new event.

<p id="gdcalert192" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image192.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert193">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>

![alt_text](images/image192.png "image_tooltip")

* You will need to select a report date before you begin this process.

You can select any report date of your choosing. This differs from aggregate data entry, in which you select a predefined period. For events, any report date can be selected.

<p id="gdcalert193" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image193.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert194">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>

![alt_text](images/image193.png "image_tooltip")

After selecting the report date, the questions within the program will appear. Note that you only see two questions as the remainder are hidden by the logic associated with the survey (or, in DHIS2 terms. the program rules).

* Fill in the following data.

Note that program rules should be triggered when you select the following questions:

* Does this facility offer family planning services?
  * Triggers the follow-up questions related to family planning services
* Received any family planning training in the last two years?
  * Triggers follow-up asking how many trained
* Received any training in adolescent sexual and reproductive health in the last two years?
  * Triggers follow-up asking how many trained
* Does this facility stock contraceptive commodities at this service site?
  * Triggers the follow-up questions related to contraceptive commodities

<p id="gdcalert194" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image194.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert195">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>

![alt_text](images/image194.png "image_tooltip")

<p id="gdcalert195" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image195.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert196">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>

![alt_text](images/image195.png "image_tooltip")

<p id="gdcalert196" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image196.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert197">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>

![alt_text](images/image196.png "image_tooltip")

<p id="gdcalert197" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image197.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert198">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>

![alt_text](images/image197.png "image_tooltip")

After entering this data you would have seen how some of the program rules work to display various items within the event capture form. If you followed along with the exercise and scroll back up to the top, you will notice some indicators have been calculated and some validation warnings have appeared along the right side.

<p id="gdcalert198" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image198.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert199">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>

![alt_text](images/image198.png "image_tooltip")

* Change the value for "How many staff are in this facility" to 15.

<p id="gdcalert199" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image199.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert200">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>

![alt_text](images/image199.png "image_tooltip")

This will remove the validation warnings and the indicators will no longer be > 100%.

<p id="gdcalert200" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image200.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert201">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>

![alt_text](images/image200.png "image_tooltip")

### Video - Event Capture Demo - Part 3 of 4 (5 min)

In this video, you will learn how the offline functionality of the Event Capture app works. This allows you to enter event data into event capture without an internet connection and synchronize it when your connection is restored.

[https://www.youtube.com/watch?v=QPm-ffywlr0](https://www.youtube.com/watch?v=QPm-ffywlr0)

#### Activity 3 - Offline entry of events

Please do this activity in [TRAININGLAND](https://live.academy.dhis2.org/tl1/dhis-web-commons/security/login.action).

* To perform offline data entry, disconnect from the internet.

DHIS2 will prompt you indicating "You are offline, data will be stored locally".

<p id="gdcalert201" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image201.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert202">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>

![alt_text](images/image201.png "image_tooltip")

    *   Try navigating around and selecting different organisation units at the facility level. You can also change between the Malaria case management or the SARA RCH program. Note that previous events will not be displayed in offline mode.

In the SARA RCH program:

    *   Register a new event with the following details.
    *   Click on "Save and go back" when you are finished.

<p id="gdcalert202" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image202.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert203">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>

![alt_text](images/image202.png "image_tooltip")

    *   Re-connect  to the internet. A prompt will indicate that "There is data stored locally, please upload to server".
    *   Click on the Upload button to upload the data.

<p id="gdcalert203" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image203.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert204">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>

![alt_text](images/image203.png "image_tooltip")

After the upload is complete, you will receive a prompt indicating that the "Upload to server was successful".

<p id="gdcalert204" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image204.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert205">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>

![alt_text](images/image204.png "image_tooltip")

### Video - Event Capture Demo - Part 4 of 4 (3 min)

In this video, we will review all of the key concepts we have discussed related to the Event Capture app.

[https://www.youtube.com/watch?v=Pi3iS3SsCLg](https://www.youtube.com/watch?v=Pi3iS3SsCLg)

## 5.3 - Tracker Programs

### Video - Tracker Programs - Tracker Programs Presentation (6 min)

In this video, you will be given an overview of Tracker programs in DHIS2. Tracker programs allow us to collect data that is attached to identifiable information. This allows this type of model to be used for the longitudinal tracking of services, commodities or other items based on the needs of the program performing this tracking.

[https://www.youtube.com/watch?v=IEEfs06GRB0](https://www.youtube.com/watch?v=IEEfs06GRB0)

### Video - Tracker Capture Demo - Part 1 of 5 (11 min)

In the first video of this series, you will start to get familiar with the **Tracker Capture app interface,** learn to **filter** cases within a program and perform simple and complex **searches** for records that already exist in the system. We will be using an Antenatal Care program example in order (ANC) to show how this works in DHIS2

[https://www.youtube.com/watch?v=_H0vrs-0ra4](https://www.youtube.com/watch?v=_H0vrs-0ra4)

#### Activity 1 - Introducing the tracker capture interface

Please do this activity in [TRAININGLAND](https://live.academy.dhis2.org/tl1/dhis-web-commons/security/login.action).

* Navigate to tracker capture by selecting Apps -> Tracker Capture

<p id="gdcalert205" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image205.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert206">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>

![alt_text](images/image205.png "image_tooltip")

* For this example, select the "Cardinal Hospital Gateway PHC" organisation unit.

<p id="gdcalert206" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image206.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert207">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>

![alt_text](images/image206.png "image_tooltip")

* Select the ANC (Antenatal care) Example program from the dropdown.

<p id="gdcalert207" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image207.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert208">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>

![alt_text](images/image207.png "image_tooltip")

This will display the entities (people in this case) associated with the program.

* Try the various filters to see how they work. From left to right, the filters are the following:
  * Only those with an event today: Filters entities who have an event scheduled today.
  * Any enrollment status: Filters all entities within the program regardless of their status.
  * Only those with active enrollment: Filters all entities that are currently receiving services within the selected program.
  * Only those with completed enrollment: Filters those entities identified as having completed the set of services offered by the selected program.
  * Only those with cancelled enrollment: Filters those entities identified as having cancelled their enrollment within the selected program (they did not receive the complete set of services and dropped out of the program).

<p id="gdcalert208" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image208.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert209">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>

![alt_text](images/image208.png "image_tooltip")

* Download Tracked Entity List: This will download the tracked entities that are displayed in tracker capture in one of XML, JSON or CSV file formats directly to your computer. It is similar to downloading events in event capture.

<p id="gdcalert209" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image209.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert210">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>

![alt_text](images/image209.png "image_tooltip")

* Show/hide columns: This will add additional columns to the tracker capture front page. These columns in tracker capture represent the attributes that are associated with the program you have selected. This differs from event capture where you saw the data elements here (event programs do not have attributes associated with them). You can access this using the "Show/hide columns" button.

<p id="gdcalert210" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image210.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert211">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>

![alt_text](images/image210.png "image_tooltip")

* Change the filter back to "Any enrollment status" and try to search for a specific entity. You can try a simple search by typing the name “Janella Thomas” in the search box.

<p id="gdcalert211" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image211.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert212">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>

![alt_text](images/image211.png "image_tooltip")

This will return the following entity

<p id="gdcalert212" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image212.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert213">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>

![alt_text](images/image212.png "image_tooltip")

You can try the advanced search as well by clicking on the drop down arrow next to the search field.

* You can use the following details to find the person:
  * First Name: Sarah
  * Last Name: Phi
  * Age: 52
  * Phone number: 0873637277

<p id="gdcalert213" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image213.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert214">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>

![alt_text](images/image213.png "image_tooltip")

This will return the following entity.

<p id="gdcalert214" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image214.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert215">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>

![alt_text](images/image214.png "image_tooltip")

### Video - Tracker Capture Demo - Part 2 of 5 (10 min)

In this video, you will learn **how to register a new entity (we are using person in this example) to a specific health program** using the Tracker capture app. You will also become familiar with the **Tracker dashboard**. This dashboard comprises all the data of one individual tracker record. From the dashboard, you will learn how to enter Tracker data.

In this video, you’ll also see what a “**widget**” is within DHIS2 Tracker.

[https://www.youtube.com/watch?v=-Q-_Nc4XThQ](https://www.youtube.com/watch?v=-Q-_Nc4XThQ)

#### Activity 2 - Register a new entity, review the dashboard and enter tracker data

Please do this activity in [TRAININGLAND](https://live.academy.dhis2.org/tl1/dhis-web-commons/security/login.action).

In the Tracker Capture app:

* Select any organisation unit at the facility level and select the ANC Example as the program.

<p id="gdcalert215" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image215.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert216">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>

![alt_text](images/image215.png "image_tooltip")

<p id="gdcalert216" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image216.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert217">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>

![alt_text](images/image216.png "image_tooltip")

* Select Register to proceed to the registration page.

<p id="gdcalert217" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image217.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert218">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>

![alt_text](images/image217.png "image_tooltip")

* In the Enrollment Page, we should try and enter unique details. You can make up some details of a person in order to fit the attributes associated with the program.
* To go through the ANC program, select an ANC registration date that is in the past. In the example here, January 1, 2016 has been selected. This will allow you go through all the ANC program stages within the ANC Example program.

<p id="gdcalert218" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image218.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert219">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>

![alt_text](images/image218.png "image_tooltip")

* When you have entered all of the details and changed the ANC registration date, click on "Save and continue." This will take you to what is referred to as the tracked entity dashboard.

Here have a look around the dashboard. The elements that were identified in the video demo are all present here. You can add/remove widgets, review the details of the person you have registered, review the timeline for data entry and enter data.

* To add/remove widgets click on the gear icon then select show/hide widgets.

<p id="gdcalert219" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image219.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert220">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>

![alt_text](images/image219.png "image_tooltip")

* You can then select the widgets to add/remove by clicking on the check-boxes next to their name. Do not remove the Timeline Data Entry widget.

<p id="gdcalert220" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image220.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert221">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>

![alt_text](images/image220.png "image_tooltip")

* Enter some data for the first program stage. To start this process, scroll down to the Timeline Data Entry widget. The first program stage is already selected and the relevant data entry page open.

The following data can be used as a guideline:

<p id="gdcalert221" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image221.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert222">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>

![alt_text](images/image221.png "image_tooltip")

* When finished with the data entry, click on the orange "Complete" button to complete this event.
* You will receive a prompt asking for your confirmation. Click on the "Complete" button to complete the first event.

<p id="gdcalert222" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image222.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert223">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>

![alt_text](images/image222.png "image_tooltip")

After doing this, the data entry for the first event will close, the event will change to grey and it will be marked as completed in the data entry timeline.

<p id="gdcalert223" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image223.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert224">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>

![alt_text](images/image223.png "image_tooltip")

### Video - Tracker Capture Demo - Part 3 of 5 (11 min)

In this video,  you will learn how to **add new events** to a Tracker record, understand the color legend within the data entry widget and review how to use additional widgets including  the **profile** and **relationships** widgets.

[https://www.youtube.com/watch?v=SNg61JBzd2A](https://www.youtube.com/watch?v=SNg61JBzd2A)

#### Activity 3 - Entering data for new events and completing the program

Please do this activity in [TRAININGLAND](https://live.academy.dhis2.org/tl1/dhis-web-commons/security/login.action).

From the previous activity:

* Select the 2nd event and continue to enter data related to the person that you have registered.

<p id="gdcalert224" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image224.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert225">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>

![alt_text](images/image224.png "image_tooltip")

* Complete the event and confirm the event is completed. Now you will be asked to schedule a follow-up visit for the mother. By default, the next visit is scheduled 60 days from the previous visit. We can use the default date here and click on "Save" to schedule the next visit.

<p id="gdcalert225" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image225.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert226">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>

![alt_text](images/image225.png "image_tooltip")

A new event will appear in the timeline according to the date in which you have scheduled the event.

<p id="gdcalert226" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image226.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert227">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>

![alt_text](images/image226.png "image_tooltip")

* Scroll back up to the top of the dashboard page and select "Complete". This blue complete button will complete the person’s enrollment in the entire program. In the context of this program, it is stating that the mother has received all of her ANC visits and will not receive anymore ANC related to this pregnancy (in reality hopefully information on more than 2 visits would have been completed).

<p id="gdcalert227" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image227.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert228">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>

![alt_text](images/image227.png "image_tooltip")

* It will ask you to confirm if you want to complete the selected enrollment. Select "Yes" to continue.

<p id="gdcalert228" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image228.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert229">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>

![alt_text](images/image228.png "image_tooltip")

The dashboard for the person will close the enrollment. In order to enter additional details you will need to Reopen the person’s enrollment in the program.

<p id="gdcalert229" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image229.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert230">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>

![alt_text](images/image229.png "image_tooltip")

If you navigate down to the data entry, you will see you can no longer edit the events.

<p id="gdcalert230" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image230.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert231">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>

![alt_text](images/image230.png "image_tooltip")

* Go back to the tracker capture front page by selecting the "Back" button on the tracker dashboard.

<p id="gdcalert231" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image231.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert232">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>

![alt_text](images/image231.png "image_tooltip")

* If you select the filter of "Only those who have completed enrollment" you will be able to see the person that you have just registered.

<p id="gdcalert232" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image232.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert233">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>

![alt_text](images/image232.png "image_tooltip")

### Video - Tracker Capture Demo - Part 4 of 5 (5 min)

When working with Tracker, we can register entities into the system without associating them with a particular service. This can be particularly useful when trying to establish a registry of some kind. In this video, you will learn how to create new records in Tracker capture that can be associated with programs as required after the record has been created.

[https://www.youtube.com/watch?v=2uex7X09Zvc](https://www.youtube.com/watch?v=2uex7X09Zvc)

#### Activity 4 - Register an entity without a program and enroll them

Please do this activity in [TRAININGLAND](https://live.academy.dhis2.org/tl1/dhis-web-commons/security/login.action).

From the tracker capture app:

* Select any organisation unit at the facility level. De-select the program by clicking on the X button next to the program name.

<p id="gdcalert233" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image233.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert234">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>

![alt_text](images/image233.png "image_tooltip")

<p id="gdcalert234" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image234.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert235">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>

![alt_text](images/image234.png "image_tooltip")

* Click on Register to register the person without a program.

<p id="gdcalert235" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image235.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert236">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>

![alt_text](images/image235.png "image_tooltip")

* Enter the details of the person and select "Save and continue".

<p id="gdcalert236" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image236.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert237">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>

![alt_text](images/image236.png "image_tooltip")

This will take you to the person's dashboard page. You must enroll them in a program now to proceed.

* Select the ANC Example program.

<p id="gdcalert237" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image237.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert238">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>

![alt_text](images/image237.png "image_tooltip")

* In the enrollment tab, select "Add new".

<p id="gdcalert238" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image238.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert239">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>

![alt_text](images/image238.png "image_tooltip")

* Fill in their enrollment details and select "Enroll" to enroll them in the program.

<p id="gdcalert239" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image239.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert240">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>

![alt_text](images/image239.png "image_tooltip")

After you Enroll them, the dashboard will start to populate with the relevant items including their profile and associated program stages.

<p id="gdcalert240" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image240.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert241">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>

![alt_text](images/image240.png "image_tooltip")

<p id="gdcalert241" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image241.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert242">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>

![alt_text](images/image241.png "image_tooltip")

### Video - Tracker Capture Demo - Part 5 of 5 (5 min)

In this video you’ll see a summary of the key concepts we have discussed as related to Tracker capture.

[https://www.youtube.com/watch?v=v3fULNNc2bM](https://www.youtube.com/watch?v=v3fULNNc2bM)

## 5.4 - Event Data Analysis

### Video - Event Data Analysis Demo - Part 1 of 4 (7 min)

You have now had the opportunity to review how individual records are entered and managed using both the event and tracker capture apps.

In this series of videos, we will review how you can analyze aggregated outputs generated from this data using the apps you are already very familiar with, pivot table and data visualizer.

[https://www.youtube.com/watch?v=3VZZK09acN0](https://www.youtube.com/watch?v=3VZZK09acN0)

#### Activity 1 - Introducing program indicators

In [TRAININGLAND](https://live.academy.dhis2.org/tl1/dhis-web-commons/security/login.action), create a pivot table including the program indicators:

* # of facilities offering ANC

* # of facilities offering family planning services

In the data tab select:

* "Program Indicators" as the data type
* "SARA RCH" as the Program
* "# of facilities offering ANC" & "# of facilities offering family planning services" as the Program Indicators

<p id="gdcalert242" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image242.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert243">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>

![alt_text](images/image242.png "image_tooltip")

In the period tab:

* Select "2016" as the period.

<p id="gdcalert243" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image243.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert244">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>

![alt_text](images/image243.png "image_tooltip")

In the organisation units tab:

* Select "District" as the organisation unit level.

<p id="gdcalert244" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image244.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert245">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>

![alt_text](images/image244.png "image_tooltip")

* Open the layout tab and:
  * Move the organisation units down to the Row.
  * Move the periods up to the filter.

<p id="gdcalert245" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image245.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert246">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>

![alt_text](images/image245.png "image_tooltip")

* Update to see the table.

Here you will see the output of indicators calculated using the responses within the SARA survey.

<p id="gdcalert246" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image246.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert247">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>

![alt_text](images/image246.png "image_tooltip")

### Video - Event Data Analysis Demo - Part 2 of 4 (5 min)

Following the previous activity, you’ll see how to use **combined indicators** to perform data analysis. These indicators combine data from the Tracker model with data from the aggregate model and can be very powerful in practice to utilize.

[https://www.youtube.com/watch?v=LE1yjF0Kyj4](https://www.youtube.com/watch?v=LE1yjF0Kyj4)

#### Activity 2 - Adding combined indicators

In [TRAININGLAND](https://live.academy.dhis2.org/tl1/dhis-web-commons/security/login.action), use the Pivot Table app to review combined indicators.

In the data tab:

* Add the following to your previous selection:
  * "Indicators" as the data type.
  * "SARA" as the indicator group.
  * "Facility offering ANC rate (%)" and "Facility offer Family Planning services rate (%)" as the Indicators.

The data tab should now include the selections from Activity 1 as well as the new indicators you have now selected.

<p id="gdcalert247" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image247.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert248">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>

![alt_text](images/image247.png "image_tooltip")

* Open the table options and:
  * De-select "Show column totals" and "Show row totals".
  * Select "Hide empty rows".

<p id="gdcalert248" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image248.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert249">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>

![alt_text](images/image248.png "image_tooltip")
=

* Select "Update" to see the table.

This table includes both the program indicators which were previously introduced as well as the combined indicators that can combine data from individual programs with other routine aggregated data.  

<p id="gdcalert249" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image249.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert250">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>

![alt_text](images/image249.png "image_tooltip")

### Video - Event Data Analysis Demo - Part 3 of 4 (5 min)

In this video, you will learn how to analyze data collected via event and tracker capture within the data visualizer app.

[https://www.youtube.com/watch?v=UBlL8E5rpZ0](https://www.youtube.com/watch?v=UBlL8E5rpZ0)

#### Activity 3 - Reviewing program data and aggregated data together

For this activity, use the Data Visualizer app in [TRAININGLAND](https://live.academy.dhis2.org/tl1/dhis-web-commons/security/login.action).

In the data tab:

* Select Indicator as the data type.
* First select "SARA" as the Indicator group and "Facility offering ANC rate (%)" as the Indicator.
* Then select "ANC" as the Indicator group and "ANC 4th visit coverage (%)" as the Indicator.

<p id="gdcalert250" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image250.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert251">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>

![alt_text](images/image250.png "image_tooltip")

In the period tab:

* Select "2016" as the period.

<p id="gdcalert251" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image251.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert252">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>

![alt_text](images/image251.png "image_tooltip")

In the organisation units tab:

* Select "District" as the organisation unit level.

<p id="gdcalert252" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image252.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert253">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>

![alt_text](images/image252.png "image_tooltip")

* Open the layout tab and:
  * Move the organisation units down to the Category; the Periods will automatically be moved to the filter

<p id="gdcalert253" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image253.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert254">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>

![alt_text](images/image253.png "image_tooltip")

* Click on "Update" to see the output.

In this chart, we have a combined indicator (Facility offering ANC rate (%)) which takes data from the SARA survey and compares it with an indicator calculated using aggregate data (ANC 4th visit coverage (%)). It is possible to perform analysis on data collected via aggregate, event or tracker processes using the concepts of program and combined indicators within the Pivot Table, Data Visualizer and GIS (Maps) apps.

<p id="gdcalert254" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image254.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert255">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>

![alt_text](images/image254.png "image_tooltip")

### Video - Event Data Analysis Demo - Part 4 of 4 (3 min)

In this video you’ll find a summary of the key concepts covered in this session.

[https://www.youtube.com/watch?v=tJOpAjCAAK8](https://www.youtube.com/watch?v=tJOpAjCAAK8)

## Assignment - Event Data Analysis

### Note: these are graded assignments. (30 min)

You are allowed 3 attempts for each of these assignments.

Instructions

You need to be logged in [TRAININGLAND](https://live.academy.dhis2.org/tl1/dhis-web-commons/security/login.action) to perform the following assignments.

Throughout these assignments, you will create a dashboard containing the following items.

The final dashboard can look something like this:

<p id="gdcalert255" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image255.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert256">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>

![alt_text](images/image255.png "image_tooltip")

#### Assignment 5.4.1

Instructions

In [TRAININGLAND](https://live.academy.dhis2.org/tl1/dhis-web-commons/security/login.action) create a chart comparing ANC 1st visit coverage (%), ANC 4th visit coverage (%), Facility offering ANC rate (%), Facilities that have been trained on ANC (%) by district for 2016

* Indicators
  * ANC: ANC 1st visit coverage (%), ANC 4th visit coverage (%)
  * SARA: Facility offering ANC rate (%), Facilities that have been trained on ANC (%)
* Period: 2016
* Organisation Units: Districts

<p id="gdcalert256" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image256.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert257">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>

![alt_text](images/image256.png "image_tooltip")

Question of the assignment 5.4.1

What were the districts in which no survey was performed? (the districts in which both Facility offering ANC rate (%) and Facilities that have been trained on ANC (%) is 0). Select one or more

* Dessert District
* Dinner District
* Fruit District
* Staple District

#### Assignment 5.4.2

Instructions

In [TRAININGLAND](https://live.academy.dhis2.org/tl1/dhis-web-commons/security/login.action) create a pivot table containing ANC 1st visit coverage (%), ANC 4th visit coverage (%), Facility offering ANC rate (%), Facilities that have been trained on ANC (%) by district for 2016.

* Indicators
  * ANC: ANC 1st visit coverage (%), ANC 4th visit coverage (%)
  * SARA: Facility offering ANC rate (%), Facilities that have been trained on ANC (%)
* Period: 2016
* Organisation Units: Districts

<p id="gdcalert257" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image257.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert258">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>

![alt_text](images/image257.png "image_tooltip")

Question of the assignment 5.4.2

Which district has the lowest ANC 1st visit and 4th visit coverage respectively?

* Cat District
* Bird District
* Fruit District
* Fish District

#### Assignment 5.4.3

Instructions

In [TRAININGLAND](https://live.academy.dhis2.org/tl1/dhis-web-commons/security/login.action) create a chart comparing the SARA reporting rate by district for 2016:

* Indicator
  * SARA: SARA reporting rate (%)

<p id="gdcalert258" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image258.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert259">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>

![alt_text](images/image258.png "image_tooltip")

Question of the assignment 5.4.3

Which district was fully surveyed? (100% reporting rate completeness in 2016)

* Dog District
* Staple District
* Cat District
* Vegetable District

## Session Quiz - Introduction to Tracker

### Session Quiz - Introduction to Tracker (20 min)

This is a **graded quiz** and it is worth **5%** of your final grade.

You have **3 attempts** to pass this test.

Select the "check" button to submit your answers.

_If you want to save your current response without submitting it for grading yet, select the "save" button. This allows you to come back later and resume the attempt._

#### Session Quiz - Introduction to Tracker

1. Tracker is meant to: (select one)

* Replace existing electronic medical records (EMR)
* Bridge the gap between the existing aggregated data and individual-level (tracker) or anonymous event based data
* Only be used for tracking patients receiving health services

EXPLANATION

Tracker programs can be used outside of the health system, and are not meant to necessarily replace an EMR. This was discussed in the tracker intro presentation.

2. What is one of the key differences between event and tracker programs? (select one)

* In tracker programs details are registered in order to follow an entity. Event programs do not include this registration
* In event programs details are registered in order to follow an entity. Tracker programs do not include this registration
* Event programs are more a more advanced version of collection individual data when compared to tracker programs

EXPLANATION

Tracker programs involve a key component of registration whereas event programs are anonymous in nature. This was discussed in the tracker intro presentation.

3. In event capture we can:

* Add in validation rules/warnings
* Add in indicators that calculate on-the-fly
* Enter data offline

EXPLANATION

All of these functions work in event capture. This was demoed during the event capture session.

4. When we enter data in event/tracker capture, we must choose a predefined period such as weekly, monthly, etc. before entering data.

* True
* False

EXPLANATION

Event and Tracker capture focus on the collection of individual-level data. If we think about a survey like SARA, or a health service like Antenatal care, we will have the individual date when a survey is performed or that a service is provided. Event and Tracker capture allow you to select an actual date when entering data rather than a predefined period. This data can be summarized using any predefined period when creating analysis outputs as required.

5. Which of the following statement(s) regarding tracker are NOT true: (select one or more)

* Tracker and event data cannot be aggregated
* Tracker and event data cannot be compared with aggregated data together
* Tracker and event capture can be audited to see what changes have been made to the data

EXPLANATION

Tracker and event data can be aggregated and analyzed in the analysis apps. They can also be analyzed together with routine aggregate data. This was shown during the event analysis session.

6. An entity (person, etc.) can only be registered in one tracker program at a time

* True
* False

EXPLANATION

A person can be registered in multiple tracker programs if required.

7. In tracker capture, we can add in relationships, such as mother-child, brother-sister, etc.

* True
* False

EXPLANATION

Relationships between various entities can be added using tracker capture.

8. In event capture, if someone comes back to the clinic with malaria more than once I can easily find their record again in DHIS2

* True
* False

EXPLANATION

Event programs are isolated events. As there is no registration component, it would be very difficult to link these events as you would manually have to find the last time they received treatment.

9. We can analyze combined indicators that use any combination of data from event, tracker or routine aggregated data entry

* True
* False

EXPLANATION

We can use combined indicators to combine any of the data types used within DHIS2. This was shown during the event analysis session.

## Feedback - Introduction to Tracker

### Feedback - Introduction to Tracker (3 min)

Please take 2 or 3 minutes to complete this feedback survey once you are done with the Module 5. Your careful response will have a real impact on how courses like this are run. Thank you!
