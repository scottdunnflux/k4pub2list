# K4 Users XML to List

A single page app to 
  - extract a user list from a K4 Users XML file
  - view and sort that list
  - download the list as CSV

## Description

Users who have access to a Publication in vjoon K4 Admin can export a Users XML file from the "Users" section of that publication.
This web app reads that Users XML file and extracts user information into a sortable list that can be downloaded as a CSV file.

A full publication XML file — exported from the "K4 Server" section of K4 Admin or included in a K4 Diagnostics package — also works, since it contains the same user data.

## Getting Started

### Dependencies

* This SPA runs on most web browsers released after 2022.

### Installing

* This SPA is available for use [here](https://scottdunnflux.github.io/k4pub2list/)
* Alternatively, the file may be downloaded and opened in a browser.

### Using k4pub2list

* Export a Users XML file from the "Users" section of your publication in K4 Admin.
  Alternatively, a publication XML file from a K4 Diagnostics package or the "K4 Server" export also works.
* Click the URL for k4pub2list:
* Upload your Users XML file
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

Contact your K4 Administrator or support provider for assistance with obtaining your K4 Users XML file.

## Authors

This SPA was developed by Scott Dunn (and AI) at [Flux Consulting, Inc.](https://fluxconsulting.com) Contact [info@fluxconsulting.com](mailto:info@fluxconsulting.com) with questions or suggestions. 

## Version History

* 2025-03-27
    * Inital version
* 2025-04-02
    * Added User Rights, Section Membership, and Client Access sections
* 2025-04-15
    * Added User Rights via Category showing when a user has rights due to the user category associated with their section membership.
* 2026-05-22
    * Overhaul interface and fix various bugs.

## License

This project is licensed under the MIT License - see the [LICENSE](License.md) file for details.

