<h1>2. Access Requests</h1>
<h2>2.1 Access Requests Page</h2>
Click the <B>Access Request</B> <img src="https://github.com/Nexcenter/NCP-Manual/blob/master/AccessRequestIcon.png"> icon to open the <B>Access Requests</B> page.
The interface displays:
<ul>
<li>Default list of up to 10 of upcoming <B>Access Requests</B> at the selected data center. </li>
<li>Links in the <B>Request Reference</B> column allow you to view, edit or cancel a request.</li> 
<li>An <B>Request Access</B> button, at top right, allows to create a new Access Request.</li>
</ul> 

<B>Access Request Information</B> section provides information to support <B>Access Requests</B> as configured by the provider. 

<B>Access Request Information</B>:
<ul>
<li> <B>Max Lead Time</B> is the maximum time in advance to request Access.</li>
<li><B>Max Reservation Time</B> is the maximum duration to request access.</li>
<li><B>Instructions</B> provide guidance, to access the data center- such as security requirements </li>
</ul>

<p align="center"><img src="https://github.com/Nexcenter/NCP-Manual/blob/master/Access%20Requests%20Page.png"></p>

<p align="center"><B>Figure: Access Requests Page</B></p>

<h2>2.2 Add an Access Request</h2>
To add an Access Request,
<ol>
<li>Click <B>Request Access</B>, from the <B>Access Requests</B> page or the <B>Upcoming Requests</B> list.</li>
<li>Enter the required details in the <B>Create Access Request</B> form.</li>
<br>
Refer to the table given below for the field details.
<table>
  <tr>
    <th>Field</th>
    <th>Description</th>
  </tr>
  <tr>
    <td>Start / End (Required)</td>
    <td>Enter the <B>Start</B> and <B>End</B> date-times. Use the calendar tools to select dates and the drop-down lists to select hours and minutes (in 15-minute intervals). <P>Note that the data center‘s <B>Max Lead Time</B> and <B>Max Reservation Time</B> constrain the specified date and time when adding an Access Request.</p></td>
  </tr>
  <td>Description of Work (Required)</td>
    <td>Provide a summary of the work to be carried out or the reason to access the data center building. <p> Depending on the data center a template may be provided in this field for guidance, the content of which should be edited as required.</td>
  </tr>
  <tr>
  <td>Bringing Equipment (Optional)</td>
  <td rowspan=3>Tick one or more option as appropriate.<p>Where <B>Escort Required</B> is ticked, click the displayed message to open a new tab and create the <B>Remote Hands Request</B> (see section 10.1). This must be done when the Access Request is created, as the setting cannot be changed once the request is submitted.</p> Failure to create the Remote Hands request when required may cause problems with your request at the data center. </td>
  </tr>
  <tr>
  <td>Removing Equipment (Optional)</td>
  </tr>
  <tr>
  <td>Escort Required (Optional)</td>
  </tr>
  <tr>
  <td>Attendees (Optional or Required)</td>
  <td>Use the Nexcenter selection widget to select attendees for the Access Request (See section 4.4.2).<p>Selection is optional if there are <B>Guest Attendees</B> (see below);otherwise at least one Attendee is required.</p><p>See also section 4.4.3 regarding Nexcenter Request contacts.</p></td></tr>
  <tr>
  <td>Guest Attendees (Optional or Required)</td>
  <td>If the Access Request is for one or more temporary visitors, rather than Nexcenter contacts, enter the <B>Guest Attendees</B> details in the fields for each guest (See section 4.4.4).<p>If there are no <B>Attendees</B>, at least one Guest Attendee must be specified; otherwise Guest Attendees are optional.</p></td></tr>
  <tr>
  <td>
    Cabs (Required)</td>
  <td>Use the Nexcenter selection widget to select the cabs associated with the Access Request (See section 4.4.2). The cabs available are those for which you have Edit Access Request permission.<p>At least one cab must be associated with the Access Request.</p></tr></td>
  </table>
 <p align="center"><B>Table: Create Access Request Form fields</B></p>
<br>


<p align="center"><img src="https://github.com/Nexcenter/NCP-Manual/blob/master/CreateAccessRequestForm.png"></p>
<p align="center"><B>Figure: Create Access Request Form (with Escort Required ticked)</B></p>

<li>Click <B>Submit</B> on completing the details. A message will be shown to confirm that your Access Request has been submitted.</li></ol> 

Once the Access Request has been submitted:      
<ul>
<li>
It is placed in a <I>Pending Response</I> state until the data center staff has processed and approved or rejected the Request.</li>
<li>It is shown in the list on the <B>Access Requests</B> page, and in <B>Upcoming Requests</B> on the Facility Information page.</li>
<li>An email notification is sent to the data center Access Request team, and to the user submitting the request.</li>
<li>If Escort Required was ticked, you must create a <B>Remote Hands Request</B> if you have not already done so (see section 10.1).</li>
<li>If the Access Request is associated with a Delivery Request or a Facility Request, the Access Request reference should be selected when the Delivery or Facility Request is created (see sections 8.2 and 9.2 respectively).</li>
</ul>

----------

<B>Note:</B> The Access Request must have been moved to Approved state by data center before your attendees can enter the data center.

-----------


<h2>2.3 View Access Request Details</h2>

To view Access Request details, click its reference e.g. ‘CAR-JP-00000001’ from the <B>Access Requests</B> or <B>Upcoming Requests</B> list.
<p align="center"><img src="https://github.com/Nexcenter/NCP-Manual/blob/master/Access%20Request%20References.png"></p>
<p align="center"><B>Figure: Access Request References</B></p>
The <B>Access Request</B> page then displays its details together with the associated Attendees, Guest Attendees and Cabs as appropriate.
<p align="center"><img src="https://github.com/Nexcenter/NCP-Manual/blob/master/Access%20Request%20Details.png"></p>
<p align="center"><B>Figure: Access Request Details</B></p>  
If the provider has rejected the Request, details may be provided in the <B>State Information</B> field. Any associated Delivery or Facility Requests appear in the <B>Associated Requests</B> section at the bottom of the page, provided you have permission for those Request types. Click the Request References to display their details. 

<h2>2.4 Edit an Access Request</h2>
If you have the permissions, you can edit an existing Access Request in the following states from the View Access Request details page:
<br>

<ul>
<li>
<I>New, Pending Response, Pending Approval, Approved, Rejected.</I></li>
</ul>

To edit an Access Request,
<ol>
<li>Click the <B>Edit Request</B> button (available when the Access Request is in an appropriate state).  
<li>Click the <B>Submit</B> button to save and apply the changes. A message confirms that your changes have been submitted.</li>
</ol>

Note that the <B>Escort Required</B> setting cannot be edited.  

After the Access Request has been edited the state is changed to <I>Pending Response</I>, the Request needs to be approved by the data center team before your attendees can enter the data center.  

<h2>2.5 Cancel an Access Request</h2>

You can cancel existing Access Requests in the following states:  
<ul>
<li><I>New, Pending Response, Pending Approval, Approved</I></li>
</ul>

To cancel an Access Request,
<ol>
<li>Click the <B>Cancel Request</B> button (available when the Access Request is in an appropriate state).</li>
<li>A confirmation dialog is displayed with a warning, where appropriate, that associated Delivery and Facility Requests will need to be updated. Click <B>Yes</B> to acknowledge and cancel the Access Request (or click <B>No</B> to leave the Access Request in place). </li>
</ol>
When the Access Request is cancelled:
<ul>
<li>The Access Request is removed from the <B>Upcoming Requests</B> list on the <B>Facility Information</B> page but shown as Cancelled on the <B>Access Requests</B> page and in Access Request searches.</li>  
<li>An email is sent to the Access Request team at the data center, and to the Customer contact who created the Access Request, confirming the cancellation and listing any associated Delivery or Facility Requests.</li> 
<li>You must edit any associated Delivery or Facility Requests, to associate them with a new Access Request (see section 8.4 or 9.4), or cancel them (see section 8.5 or 9.5).</li>
</ul>

-----------

<B>Note:</B> Once <I>“Cancelled”</I> the Access Request can no longer be edited.

--------------

<h2>2.6 Search Access Requests</h2>

To search for Access Requests,
<ol>
<li>Click the Search icon <img src="https://github.com/Nexcenter/NCP-Manual/blob/master/SearchIcon.png"> and select the <B>Access Requests</B> tab.</li>
<p align="center"><img src="https://github.com/Nexcenter/NCP-Manual/blob/master/SearchAccessRequest.png">
<p align="center"><B>Figure: Search Access Requests</B></p>  
<li>Enter your search criteria. All fields are optional, to narrow down your search enter all the field values </li>
<table> 
  <tr>
    <th>Field</th>
    <th>Description</th>
  </tr>
  <tr>
    <td>Authorisation Number</td>
    <td>Enter all or part of the authorisation number.</td>
  </tr>
  <tr>
    <td>Start</td>
    <td>Select the start date-time to search from (inclusive). See Section 7.6.1.</td>
  </tr>
    <tr>
    <td>End</td>
    <td>Select the end date-time to search to (exclusive). See Section 7.6.1.</td>
  </tr>
     <tr>
    <td>Requested By</td>
    <td>Enter name of the person submitting the request or part of the name.</td>
  </tr>
  <tr>
    <td>State</td>
    <td>Click the field and select a Request state from the drop-down list. Repeat to select multiple states. To remove a state from the search, click  ‘x’.</td>
  </tr>
     <tr>
    <td>Attendee</td>
    <td>Enter the name, or part of the name, of an attendee.</td>
  </tr>
   <tr>
    <td>Description of Work</td>
    <td>Enter content as appropriate to filter Access Requests by work description.</td>
  </tr>
  <tr>
    <td>Bringing Equipment</td>
   <td rowspan=3>Include or exclude the options in the search by clicking the boxes and cycling through the following states: <ul><li>Grey (default): Requests are returned whether or not they have the option selected.</li><li>Ticked: only Requests with the option selected are returned.</li><li>Blank: only Requests with the option not selected are returned.</li></ul>
  </td>
  </tr>
  <tr>
  <td>Removing Equipment</td>
  </tr>
  <tr>
  <td>Escort Required</td>
  </tr>
  </table>
  <p align="center"><B>Table: Access Requests Search Criteria </B></p>
  <li>Click the <B>Submit</B> button.</li></ol>  
 
 The search results appear in a list below the search criteria fields.  By default the oldest items first are shown. <p>Click a column heading to sort by that column. <p>To display details of an Access Request, click its <B>Request Reference.</B>
 
 <h3>2.6.1 Search by Date</h3>
All Nexcenter Requests and Access Logs can be searched by date.
To search by date,
<ol>
<li>Click the <B>Start</B> or <B>End</B> field.</li>
<li>Select a date from the pop-up calendar. To scroll through the calendar, click the arrow buttons.</li>
<li>Either accept the default time (00:00) or use the hour and minute drop-down lists. Minutes can be selected in 15-minute increments.</li>
<li>The pop-up calendar is closed when the date is clicked (or by clicking the page outside the calendar if the date is already (selected).</li>
</ol>

-------------

<B>Note:</B> The <B>Start</B> date-time is inclusive, while the <B>End</B> date-time is exclusive. For example a search starting at 10:00 and ending at 17:00 will return Requests or access events that occur between 10:00 and 16:59; events starting at 17:00 will not be returned.

--------------
  
<h2>2.7 Search Access Logs</h2>
The Access Logs may be searched for details of a data center access or gate access event. Data center access events relate to the data center building, while gate access events relate to a room or cage within the data center building.  

To find access events,
<ol>
<li>Click the <B>Search</B><img src="https://github.com/Nexcenter/NCP-Manual/blob/master/SearchIcon.png"> icon.</li> 
<li>Click the <B>Access Logs</B> tab.</li>
<p align="center"><img src="https://github.com/Nexcenter/NCP-Manual/blob/master/SearchAccessLogs.png"></p>
<p align="center"><B>Figure: Search Access Logs</B></p>
<li>Enter your search criteria. All fields are optional, but will help narrow down your search if completed.</li>

<table>
  <tr>
    <th>Field</th>
    <th>Description</th>
  </tr>
  <tr>
    <td>Room</td>
    <td>Enter the room number in full (to filter gate access events only).</td>
  </tr>
  <tr>
    <td>Start</td>
    <td>Select the start (entry) date-time to search from (inclusive). See Section 7.6.1.</td>
  </tr>
  <tr>
    <td>End</td>
    <td>Select the end (exit) date-time to search to (exclusive). See Section 7.6.1.</td>
  </tr>
  <tr>
  <td>Card Number</td>
    <td>Enter the visitor’s card number in full (Letters are case sensitive).</td>
  </tr>
  <tr>
    <td>Visitor</td>
    <td>Enter the name, or part of the name, of the visitor.</td>
  </tr>
  <tr>
    <td>Visitor Company</td>
    <td>Enter the name, or part of the name, of the visitor company.</td>
  </tr>
  <tr>
    <td>Acceptance Number</td>
    <td>Enter the acceptance number in full.</td>
  </tr>
  </table>
  <p align="center"><B>Table: Access Log Search Criteria form fields</B></p>
  
<li>Click the <B>Submit</B> button.</li></ol>

By default the oldest items appear first  in the results. <p>Click a column heading to sort by that column. <p>Separate lists are returned for data center and gate access events.<p>Note that the start and end time appear for each gate or data center access event in the report. Where the value is not available, the column can be blank.</p>
<p>
Click the <B>Export</B> link seen at the bottom of each list to export the returned results as a CSV file. </p>

 
