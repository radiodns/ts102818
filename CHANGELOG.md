# v3.5.1 (2023-12)
- creation date for logo objects to improve version control;
- addition of attribute _language_ to define presentation language for services and schedule, programme, programme events and clarification of the use of
xml:lang in the SPI

## new section
### 5.16 presentationLanguage
- defines the presentation language(s) of a service, schedule, programme, programmeEvent
- the attribute _primary_ is used to define the primary language

## amended sections
### 5.5 link element
- addition of _language_ attribute to define the language of the linked content

### 5.8 multimedia element
- addition of _language_ attribute to define the content language of the multimedia object
- addition of _creationTime_ attribute to allow for more accurate caching of multimedia objects on the receiver

# v3.4.1 (2022-05)
- Phonetic definition of service names and programme titles for voice-controlled applications;
- Service name aliases to improve discovery;
- Definition of programme contributors and credits;
- Guidance on using IP bearers carrying playlist files or adaptive streaming;
- Guidance on how to support information for regional and supra-regional services.

## new sections
### 5.14 alias element
### 5.14 phoneme element
- elements to aid voice recognition / reproduction functionality

### 7.14 credits element
### 7.15 credit element
### 7.16 organization element
### 7.17 person element
- elements to allow presenters and contributors to be specified for programmes/programmeEvents

### E.6 Supra-regional and regional services
- Guidance on the use of supra-regional and regional RDS PI Codes

## amended section
### 5.11.4 IP-based
- how to interpret combinations of URI and mimeValue to discover the stream transport method

# v3.3.1 (2020-08)
- Addition of "geo-fencing" capabilities to streaming bearers

## amended section
### 5.12 geolocation element
- Addition of a new attribute _allow_ to gelocation elements which are children of bearers defining IP streams.

This allows Service Providers/Broadcasters to define regions in which IP streaming is permitted/available or not-permitted/not-available.

# v3.2.1 (2019-06)
- Addition of Client Identification to control access to SPI documents.

Client Identification allows the Service Provider/Broadcaster to issue unique Client IDs to individual users to authenticate their access to SPI documents.

## new sections
### 10.2.2.1 Lookup using the Authoritative FQDN - Introduction
### 10.2.2.2 Services not supporting client identification
### 10.2.2.3 Services supporting client identification
### 10.5.5 Client Identification
- The process of providing a Client ID parameter when requesting an SPI document.

# v3.1.1 (2015-01)
- First version with RadioDNS functionality

## new sections
### 5.11 bearer element
- Definition of DAB/DAB+. DRM and IP bearers

### 9 Delivery of SPI over DAB/DRM
- Restatement of how to provide SPI using a DAB or DRM data channel
 
### 10 Delivery of SPI over IP
- New definition of how to discover and retrieve SPI using RadioDNS lookups over IP


This version was a substantial re-write from the preceeding version (v1.5.1) so all heading numbers have been changed, and content rearranged.
