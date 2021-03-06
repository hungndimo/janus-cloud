Changelog
==============

All notable changes to this project will be documented in this file.

 [v0.3.0]  - unreleased
---------------------------------
* add rtp_forward operations to the admin API of videoroom plugin
* Add support for VP9 and H.264 profile negotiation for videoroom and echotest plugin
* Added support for multichannel Opus audio (surround) for videoroom
* Added VideoRoom option to only allow admins to change the recording state
* Enable / disable recording while conference is in progress for videoroom

 [v0.2.0]  - 2020-05-10
---------------------------------

* Janus-proxy support api_secret authorization
* Janus-sentinel support admin_secret for sending admin API request
* The APIs of Videoroom, Videocall, P2pcall is compatible with Janus-gateway of v0.9.2
* support rtp_forward feature for videoroom


 [v0.1.0]  - 2020-03-29
---------------------------------

* initial version released
* janus-proxy and janus-sentinel are finished
* echotest, videocall, p2pcall, videoroom plugins of janus-proxy are ready
