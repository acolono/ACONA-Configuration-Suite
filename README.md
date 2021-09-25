# ACONA Configuration Suite

Provides a userinterface for configuration like ACONA Success Score definitions.

# About ACONA

ACONA stands for Augmented Content Analytics - an open source tool that automatically analyzes and simplifies data, for example from server logs or existing (open source) analytics tools, and proposes concrete measures for optimizing content.

More in the general documentation: https://app.gitbook.com/@acolono/s/acona/

# About ACONA Configuration Suite

This is part of the Admin Backend, where user can register and configure data sources, page types, domains and urls that should be analyzed.

It is based on groups module, to support multiple users by domain.

After log in users can create a domain. For a domain data source can be activated (like Matomo or Google Search Console),
Page Types can be defined with specific Success Score definitions, and URLs can be defined.

## Success Score Calculator

A very specific feature is the Success Score definition for Page Types.
For example you can say that you have Page Type "Landingpage", for which a combination of Organic Clicks and a low Bounce Rate defines the Success Score.
For each of these variables a relevance and a type can be assigned. This way the system can calculate an ACONA Success Score between 1 and 100
for URLs. 
