# K4 Publication XML to List

A single page app to 
  - extract a user list from a standard K4 Publication XML file
  - view and sort that list
  - download the list as CSV

## Description

vjoon K4 Server sofware allows K4 Administrators to download a publication XML file
that contains all settings necessary to create an entire publication. 
This web page application makes use of that publication xml file extracting a subset of that information to create a user list
that can be download as a CSV file.

## Getting Started

### Dependencies

* This SPA runs on most web browsers released after 2022.
* This SPA requires an internet conncetion to load JavaScript and CSS libraries.

### Installing

* This SPA is available for use [here](https://scottdunnflux.github.io/k4pub2list/)
* Alternatively, the file may be downloaded and opened in a browser.

### Using k4pub2list

* Obtain a K4 publication XML file. This can be found in your diagnostics package or exported from 
  the publication section of the `K4 Server` tab of K4 Admin.
* Click the URL for k4pub2list:
* Upload your publication XML file
* Hide/Show columns as needed
   - Note the "Toggle All" check box.
   - Toggle sections or scroll through the boxes to see
      - User Rights
      - User Rights via Category (to see which rights are infered through section membership user categories)
      - Section Membership
      - Client Access
* Sort columns by clicking the column header clicking additional times to change the order of the sort.
* Hold shift key while clicking column headers to add the column as a secondary sorting column.
* Click `Export CSV` button to download the list as a CSV file.

## Help

Contact your K4 Administrator or support provider for assistance with obtaining your K4 Publication XML file.

## Authors

This SPA was developed by Scott Dunn at [Flux Consulting, Inc.](https://fluxconsulting.com) Contact [info@fluxconsulting.com](mailto:info@fluxconsulting.com) with questions or suggestions. And a lot of help from AI.

## Version History

* 2025-03-27
    * Inital version
* 2025-04-02
    * Added User Rights, Section Membership, and Client Access sections
* 2025-04-15
    * Added User Rights via Category showing when a user has rights due to the user category associated with their section membership.

## License

This project is licensed under the MIT License - see the [LICENSE](License.md) file for details.

