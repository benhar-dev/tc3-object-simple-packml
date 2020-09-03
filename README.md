# Example a simple packml implementation using inheritance

## Disclaimer
This is a personal guide not a peer reviewed journal or a sponsored publication. We make
no representations as to accuracy, completeness, correctness, suitability, or validity of any
information and will not be liable for any errors, omissions, or delays in this information or any
losses injuries, or damages arising from its display or use. All information is provided on an as
is basis. It is the reader’s responsibility to verify their own facts.

The views and opinions expressed in this guide are those of the authors and do not
necessarily reflect the official policy or position of any other agency, organization, employer or
company. Assumptions made in the analysis are not reflective of the position of any entity
other than the author(s) and, since we are critically thinking human beings, these views are
always subject to change, revision, and rethinking at any time. Please do not hold us to them
in perpetuity.

## Overview
Super simple worked example of using a packml station.  This has a single T_LidApplyStation which extends the T_Station class. The base packml tries to return to IDLE.  By overriding the protected methods you can modify it's behavior.

This is not a full implementation of Packml as this does not utilize modes or any of the structures required, but is intended only as a simple example. 

There is also an initialize set of methods which is also outside of packml scope.  

## Install 
Not required.  Simply open the project.

## TwinCAT
This project uses TcXaeShell 3.1.4024.10

## Getting started
This is not a guide for TcXaeShell, please visit http://beckhoff.com/ for further guides