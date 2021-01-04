# Advanced Group Tool
The Advanced Group Tool can be used instead of the default Groups tool in Blackboard. The AGT allows instructors to quickly create and manage a large number of groups. Students can either sign up for groups themselves, or the AGT can divide students into each group. Furthermore, import and export functionality is provided.

This building block requires a license key. Please contact Nestorsupport (nestorsupport@rug.nl) for any questions.

## Links
- [Download Latest Release](https://github.com/rijksuniversiteit-groningen/b2-AdvancedGroupTool/releases/latest)
- [View All Releases](https://github.com/rijksuniversiteit-groningen/b2-AdvancedGroupTool/releases)

## Release Notes

### 3800.210104.0
* fixes MissingResourceException in Blackboard 2019 Q4 CU7 and Blackboard 2020

### 3800.200508.0
* compatible with Blackboard 2019 Q4; compiled with Java 11 so *not* compatible with older Blackboard versions
* support the Bb Collaborate tool as Blackboard does in its own group management
* Forum and Collaborate settings of a group set are used when a student adds a new group to a self enroll page
* give proper error message when instructor tries to import an encrypted Excel file

### 3400.190904.0

- compatible with Blackboard 2018 Q2, 2018 Q4 and 2019 Q2
- importing from Excel that contains external references will now give user a message instead of a blank page (and spamming the admin)

### 3400.181201

- release for Blackboard 2018 Q2 (aka version 3400.0.x)
- options for logging to directories used by Blackboard SAAS or an Elastic server
- fixed batch import using Excel 2007
- disabled disk cache as the DiskExpiryTask causes ClassNotFoundException

### 3000.170314

- Fixed error message 'Unable to find taglib ng for URI: /bbNG', building block is now compatible with Blackboard Q2/Q4 2016 releases.
