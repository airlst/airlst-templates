#AirLST Email Templates

__Keywords:__ Restaurant, Reservation, Booking, Widget, Online, Reservation

##Summary
AirLST (pronounced *airlist*) allows you to easily accept online reservations from your website. This repository contains templates for customized reservation response emails.

##Usage
To send customized emails for reservation confirmations use our default template provided with this repository. You can fully customize the appearance and styles, but keep in mind that optimizing appearance for different email clients can be PITA.

You can use specific placeholder tags within the template which will be filled with the corresponding data.

Generally, we support only one template per account. All content needs to be provided by using placeholder tags. To make an example: Both acceptance and rejection emails will use the same general template, but have different content (acceptance/rejection) based on the placeholder tags.


##Placeholder tags
Use one or several of the following tags to customize your response email.

####\*|FIRMA|\*

*Description:* Displays the name of the company that owns the account.

*Example:* Pizzeria Da Marco


####__\*|NAME|\*__ 

*Description:* Displays the name of the person who made the reservation request

*Example:* Franz Müller


####__\*|STATUS|\*__ 

*Description:* Displays a text which indicates if the reservation has been accepted or rejected. In German, this text will contain a formal address ("Sie").

*Example (if accepted):* Vielen Dank für Ihre Reservierungsanfrage, die wir hiermit gerne bestätigen.
 
*Example (if rejected):* Vielen Dank für Ihre Reservierungsanfrage, die wir leider nicht bestätigen können.

####__\*|STATUS_DU|\*__ 

*Description:* Displays a text which indicates if the reservation has been accepted or rejected. In German, this text will contain a personal address ("Du").

*Example (if accepted):* Vielen Dank für Deine Reservierungsanfrage, die wir hiermit gerne bestätigen.
 
*Example (if rejected):* Vielen Dank für Deine Reservierungsanfrage, die wir leider nicht bestätigen können.

####__\*|TIME|\*__ 

*Description:* Displays the time of the reservation.

*Example:* 18.30


####__\*|DATE|\*__ 

*Description:* Displays the date of the reservation.

*Example:* 24. Dez 2012


####__\*|PAX_PLANNED|\*__ 

*Description:* Displays amount of people for this reservation.

*Example:* 3


####__\*|MSG_RESPONSE|\*__ 

*Description:* Displays a customized message to the guest which is sent with the acceptance / rejection.

*Example:* Vielen Dank, wir freuen uns auf Ihren Besuch.


####__\*|DETAILS_TEXT|\*__ 

*Description:* Displays a preformatted table of all relevant information about the reservation. (Used for convenience.) Output will be standard text (not HTML).

*Example:* 

Datum: 24. Dez 2012

Uhrzeit: 18.30

Anzahl Personen: 3

Mitteilung: Vielen Dank, wir freuen uns auf Ihren Besuch.



####__\*|DETAILS_HTML|\*__ 

*Description:* Displays a preformatted table of all relevant information about the reservation. (Used for convenience.) Output will be HTML-formatted and have bold row names.

*Example:* 

__Datum:__ 24. Dez 2012

__Uhrzeit:__ 18.30

__Anzahl Personen:__ 3

__Mitteilung:__ Vielen Dank, wir freuen uns auf Ihren Besuch.




##Examples

* AirLST default template [request-reply-template.html] (request-reply-template.html)

##Prerequisites

None, except…

…to use AirLST, sign up for a free test account. You can manage reservations through our app and web backend (paid). Accepting reservations by email is free of charge and will always be.

Details on [www.AirLST.com] (http://www.airlst.com/web/reservationbook)

(English version will be available shortly)

##Copyright
2011-2013 AirLST by LINKS DER ISAR GmbH

All rights reserved. AirLST is a registered trademark of LINKS DER ISAR GmbH.

[LINKS DER ISAR](http://www.linksderisar.com) ist eine [Online Agentur München](http://www.linksderisar.com).