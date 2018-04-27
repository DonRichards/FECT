# **F**ront-**E**nd **C**oding **T**est

## About the Exercise

The following exercise will be used to help evaluate candidates for [UT Libaries Digital Initiative's]() vacant front end developer position. This exercise is intended to only take a few hours to complete.

If any parts of the exercise are unclear or outside your expertise, feel free to move forward to the next part. Please use your own professional discretion when deciding what parts of the exercise to focus on.

While forking to GitHub is not required, please add your commits along with the current Git repository to some online repository service and share it with the search committee at least 24 hours in advance of your interview.  If you need to make the repository private, please contact us and we will provide you with our account information so we can be given read access.

## Scenario

You have been asked by the Libraries' Web Interface Group to follow the [marketing team's design proposal](website_mock-up.pdf) to modify an existing web page that shows a list of digital collections. Each collection object is represented by a __figure__. To do this, you are not allowed to modify the index.html page's structure or the order in which each figure is found in the html. Otherwise, you can add or modify anything you need. The committee has given you the following list of action items:

1. Convert the webpage from a list view to a grid layout
2. Ensure the new design is responsive in terms of width
3. Add a feature to make the figure's title display when a user's mouse hovers over it
4. Ensure the feature makes so the title no longer displays when the mouse is no longer hovering over the figure
5. Add functionality to the drop down menu to allow you to filter the DOM to only show figures associated with the selected group.

Marketing Team's Design Proposal [PDF is here](website_mock-up.pdf)

## How to start
You will need to have a Github account to complete this.

*   Fork this repo to your profile (USERNAME/FECT).
    * If privacy is a concern, feel free to push the existing project to a new repository in [BitBucket](https://bitbucket.org/) and share the link with the search committee.
*   Make any necessary changes to implement the expected outcome
*   Push all commits to your remote repository prior to your interview
*   Follow the design instructions as close as possible
    *    Change the list view to a grid of figures with titles hidden until a hover event is executed.
    *    Modify the drop down menu to hide everything except figures associated with the group.
*   Follow the **WAI-ARIA 1.0** standards as much as possible
    *   The tab index should go from left to right then down to the next row.
*   Use the wireframe provided by the marketing department

## Files Provided

These skeleton files are provided:

*   [index.js](index.js)
*   [custom.css](custom.css)
*   [script.js](script.js)


 You are not limited to these. Feel free to create any additional files you may need.


### Collection Groups Table

<table>
  <tr>
   <td>Great Smoky Mountains Regional Collections
   </td>
   <td>Modern Political Archivess
   </td>
   <td>Tennessee Historical and Regional Collections
   </td>
   <td>University Archives Collections
   </td>
  </tr>
  <tr>
   <td>Albert "Dutch" Roth Photograph Collection<br/>
   Fifty Years in Cades Cove<br/>
   From Pi Beta Phi to Arrowmont<br/>
   Panoramic Images of Elgin P. Kintner, M.D.
   </td>
   <td>Phoenix<br/>
   Publications By Students
   </td>
   <td>Blount County Historical and Architectural Inventory<br/>
   Charlie Daniel Editorial Cartoon Collection<br/>
   Henry Pippitt Diaries
   </td>
   <td>Commencement Programs<br/>
   Humming Humbug<br/>
   Tennessee Football Programs
   </td>
  </tr>
</table>

## What are we looking for

* Attention to detail and ability to follow written instructions
* Ability to keep project within the limits and needs of the request
* Ability to understand and implement basic accessibility standards
* Ability to create a grid view with up to 4 figures across

### Out of scope / Not necessary

* The figures or any part of your design are NOT expected to link to any existing collections. The empty anchors are just for display.

## Final Product
Final product should roughly look and behavior like this.
![Behavior](https://i.imgur.com/PPMFZ84.gif)
