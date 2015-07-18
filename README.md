# xdjabberd
[XMPP/Jabber Service] xdjabberd

## TODO list
* Add SIP protocol enhance voice quality
  - reference [combining-sip-and-xmpp](http://www.onsip.com/about-voip/sip/combining-sip-and-xmpp)
  - an online example [getonsip](https://www.getonsip.com/)
  - an android client [CSipSimple](https://play.google.com/store/apps/details?id=com.csipsimple&hl=en) Package [On F-Droid](https://f-droid.org/repository/browse/?fdid=com.csipsimple)
  - Another example [Ring](http://ring.cx/)
* Audio call bitrate  
  current audiocall bitrate is toooooooo low!  
  Set up SIP, or try to look into XMPP voice bitrate.  
* Migrate from openfire to ejabberd
* write doc/tutorial
  - install guide
  - pidgin tutoral
    - contactcs
    - groups
    - conference
    - file transfer tutorial
    - voice tutorial
* add utf-8 head to solve wrong encode
* add this project link in xdlinux's homepage
* do advertising
* client for xmpp (voice and video)
  - client for android
    - conversations [OK]
  - client for ios
  - client for linux
    - gajim [OK]
	- GAIM
	- pidgin [OK]
	- empathy [OK]
  - client for mac
  - client for windows
* QR code for easy install
* QR code for easy sign up
* QR code for easy add friend
* QR code for easy add groups

## Tests
### Openfire Test Results (will be obsolete)

* Linux+Gajim - with - Linux+Gajim
  - text [OK]
  - voice [OK] - bitrate low
  - files via 5222 [OK] - slow
  - files via 7777 [OK] - very good
 
* Linux+Gajim - with - Android+Conversations
  - text [OK]
  - voice [?]
  - images [OK]
  - audio clips [OK]

### Ejabberd Test Results (Migrating)

* Linux+Gajim - with - What

## Rules
* If any user encounterd related problem, let him report/open an issue here, the xdjabberd repo.
* Registration is only available in the school network.
* xmpp client login is available globally, no IP restrictions at this point.

## Policy
* End users must not violate the law with our service.

## Copyleft
* Server: openfire (opensource) -> ejabberd (free software)
