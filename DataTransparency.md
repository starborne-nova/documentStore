This is the Data Transparency Policy for the Starlight/Jabroni Notify Chrome Extension

# Disclaimer: This is not a legally binding document and is provided solely for informative purposes

## Intro

Due to numerous recent incidents of many people not understanding what data constitutes as Personally-Identifiable and not knowing how data processing on servers as a whole works, This document seeks to clarify the process and how end-user data is handled.

The following abbreviations are used to describe parts of the data processed by the server:

CI - Connection Identifiable: This is data that represents your public address used to send and recieve data through a connection

DI - Device Identifiable: This is data that represents a unique identification for the device used to access the Internet

PI - Personal Identifiable: This is data that can be directly traced to a person. Examples include User account names, User display names, Profile pictures. This data is often public record

PP - Personal Protected: This is data that can identify and authorize a person to take protected actions. Examples include: A username and password pair used to log in to an account


## Data sent to the server

The extension contacts the server at set intervals to get the most recent information available. This is the foundation of how the extension works. The server handles data sent from Twitch, and the server parses and sends this on to the extension.

The extension sends CI data to the server as well as a block of data that identifies it's origin as the extension.

The server responds with CI data to the extension with the most recent Twitch information.

The server logs all incoming and outgoing connections in volatile storage. There is only CI data contained in these logs.

In the case of Starlight, data is sent to the server and relayed to Twitch to retrieve followed users. Your Twitch username will show up in CI data in the log, but this data is volatile and is not stored

## Data that is handled by other parties

Connection-relevant data that is handled by other parties means handling that is completely out of my personal control. This is data handled by your ISP, Network filters, and anything else that has access to your network.

This commonly includes CI and DI data that is used by an ISP to facilitate internet access. My server does not collect any PI data for analysis but there are millions of factors that can determine if other parties collect this data.

## Data that is not sent to the server

The server does not request or store DI, PI, or PP information. Your twitch information is not stored or linked to your extension use.

