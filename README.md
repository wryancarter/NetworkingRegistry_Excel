# NetworkingRegistry_Excel
An Excel workbook that helps track Networking efforts with some simple automated features.

This document is a walk through and explanation of the inputs and features of the Networking Registry Workbook.
# Networking Registry Worksheet
This worksheet is the front page of the document.  This is where all contacts are stored and you will do most of the work on the document.  It also displays reminders to reply or checkin with contacts.
  Name Column
    Input the name of your contact
  "-" Column
    Displays a notification that tells you whether you are up to date with the contact(green), should check-in with the contact(yellow), or need to reply to the contact(red)
  Status Columm
    Displays one of a list of terms that determine how active you are with that contact.
      - Hot means you've heard from the contact within the last 30 days
      - Warm means you've heard from the contact within the last 120 days
      - Cold means you haven't heard from the contact within the last 120 days
      - Contacted means that you have reached out but have never heard back from the contact
      - Blank or Null indicates no dates present in either the 'Contact Date' column or the 'Last Heard From' column.
  Connection Column
    Input the way you know or are connected to the contact (not tied to any current or planned features)
  Relationship Column
    Input from a list to determine how close you are to a contact (not tied to any current features)
  Current Position Column
    Input for the contact's current possition
  Current Company Column
    Input for the contact's current company (input these consistently)
  Additional Position Notes Column
    A place to keep notes about a contact's secondary position or other details
  Contact Date Column
    Input for the date you last sent some form a communication to the contact
  Last Heard From Column
    Input for the date you last heard from the contact
  Contact Platform Column
    Input for the platform of the most recent contact from a list
  Description of Contact? Column
    A place to keep notes about your last interaction with the contact
  LinkedIn Column
    Input for whether the contact is connected on LinkedIn or not.
    
# Registry Backend Worksheet
  This worksheet is a hidden sheet that mirrors some of the information from the Front End and performs longer uglier calculations before passing them back to the Front End.  Not incredibly necessary right now but will be useful to keep the front end clean while upcoming features are being implemented.

# Preferences Worksheet
  This worksheet allows for customization options of the previously defined Contact status and how often you should be reminded to follow up with a contact.  The Check In Override function is not yet implemented, neither is the Respond Times by Platform.  Top 10 Companies feature is only half way implemented but is a place for you to input the top 10 companies you'd like to work for.
  
# Stats Worksheet
  This worksheet has no inputs and is purely for fun.  If you capture details from this while using the worksheet overtime you will likely see significant improvements in your metrics!  It also displays the number of contacts you have working at your top 10 companies.
