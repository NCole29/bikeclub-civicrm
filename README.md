# Bike Club - CiviCRM Recipe

## Overview

This recipe installs CiviCRM and related Drupal modules.

## Drupal Modules Installed to Work with CiviCRM

Module | Description
-------|------------
CiviCRM entity		| Expose CiviCRM entities as Drupal entities.
CiviCRM member roles| Sync CiviCRM Contacts with Membership Status to a specified Drupal Role.
CiviCRM group roles	| Sync Drupal Roles to CiviCRM Groups.
Webform CiviCRM		| Webform integration with CiviCRM.

## Features of Installed Configuration

**CiviCRM entities**
CiviCRM information about contacts, members, and event registrations is exposed to Drupal and used in "Views" accessed from links on the People page.

**Member Roles**
The system is configured to create a Drupal USER account for club members when members when member registration is complete. Members may log in to access account information (membership expiration date, event registrations) and member-only content, if it exists.

**Group Roles**
If a CiviCRM mailing list ("group") is maintained for Ride leaders, this group may be sychronized with the Drupal "Ride leader" role. 