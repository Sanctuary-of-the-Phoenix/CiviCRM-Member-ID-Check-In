# CiviCRM-Member-ID-Check-In
Unique Member ID's and Check-in to Locations and Events

This plugin is in conceptual stages. This is not anywhere near release.

This extension aims to provide robust resource management and attendance management in CiviCRM.

# Scope:
1. Create unique Member ID's to be in an individual's contact information.

2. Create templates to create Membership Cards that have a QR code element containing the Member ID.
These can be digital, printed, sent to a print shop, or used in plastic cards with optional RFID, Barcode, NFC, and Magnetic Strip.

3. Create and impliment UI and Database changes to allow for an Organization to have more than 1 building and to have multiple rooms.
The Database will keep a record of Member Check-ins at buildings and rooms. These records can be exported to CSV and Spreadsheet.

4. Create and impliment UI and Database changes to allow for an Organization to manage resources like books or equipment, and have a Member able to Check-out such resources.

5. Integrate with existing CiviEvents component to extend the ability for a Member to Register for an Event and Check-in to update attendance through the use of this extension.

6. Have an intuitive interface for an orginizational attendant or kiosk to manage Check-ins and resource Check-outs.

7. Set permissions for an Admin to determine which Membership Types are granted a Member ID.

8. Set permissions for which Membership Types may Check-out resources but also manage which Members may Check-out resources. Choice between allowing all Members to be provisioned within a Membership Type or manually provisioning each approved Member of a Membership Type.

9. Integrate QR Code Scanning, Barcode Scanning, RFID Scanning, NFC Scanning, and Magnetic Strip Scanning to seemlessly authenticate at Kiosks or Attendants without having to interact for Check-ins while verifying the sucessful Check-in, only presenting more options for Event Registration or resource Check-Out.

10. Make it so features that do not depend on eachother can be turned off for configuration. I.E if an Admin only wants to use the Member ID feature.

11. Make it play nice with:
https://github.com/progressivetech/net.ourpowerbase.qrcodecheckin
and
https://lab.civicrm.org/extensions/civimobileapi / https://civimobile.org/

12. Make optional integrations for other CiviCRM Extensions such as https://github.com/civicrm/org.civicrm.volunteer


More features to be determined.
