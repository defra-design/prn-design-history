---
title: Enrolment journey
description: This post is about enrolment journey and changes made specifically for PRN
date: 2023-06-09

---


We are re using the enrolment flow which was designed by the Report packing data team with a few small changes for our users.

We removed any reference to RPD from the [prototype](https://defra-cpr-prototype.herokuapp.com/prn/account-creation/build/azure-b2c/sign-in).

![userflow for enrolment](/userflow-enrolment.png)


We added a extra questions to the end of the flow to ask them for NPWD number, this will allow DEFRA to identify and match with the account from the legacy system.

![userflow for enrolment](/NPWD-number.png)
