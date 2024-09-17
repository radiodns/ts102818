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
