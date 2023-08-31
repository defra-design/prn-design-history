---
title: First iteration based on the first round of research on regulator prototype
description: This post is about first iteration based on the first round of research on Regulator prototype sprint 6
date: 2023-08-23

---



This post is about first iteration based on the first round of research on regulator prototype.





### Organisation details

Users needed to be able to differentiate between Registered (Companies House) address, Business/Head Office address (if different to Registered) and Site address(es) - Changed ‘Company address’ to ‘Registered office address’

Users also specified that they would like a contact for the registered address, but before adding this, we need to investigate how to get this from the registration journey when that is designed.

![organisation details](/org-details.png)


### User details

Users were confused by some new terminology around user types and roles that don't align to NPWD terminology, so we changed to ‘Authorised’.

Regulators would expect to see the role, job description or relationship between delegated users and the organisation (this particularly applied to consultant users) - we don’t currently collect this, needs changes to EPR enrolment.  

Job titles and phone numbers would be useful for all users. Again, we don’t currently collect this, needs changes to EPR enrolment.

Users had an expectation of being able to add, remove or amend users and user details. We need further investigation to see what is appropriate and possible.  

![user details](/user-details.png)





### Changed revoke to cancel

Users didn’t understand revoke, they know it as ‘cancelling’, so we changed ‘revoke’ to ‘cancel’

Success page - changed from ‘revoke’ to ‘cancel’

As per user feedback on not wanting the system to notify users that they were being suspended or cancelled, we removed the line about emails being sent. The regulators prefer to handle this messaging and communication themselves offline.  

Reactivating an accreditation after revoking it has been removed, as it is not how the process works. They must reapply for accreditation.  

![cancel](/revoke.png)
