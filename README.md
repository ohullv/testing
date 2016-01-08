__tsip_transport_ws_onmessage
recv=INVITE sip:2004@45.58.32.215:10060 SIP/2.0
Via: SIP/2.0/WSS 45.58.32.215:443;rport;branch=z9hG4bK-2062457853
From: <sip:ZIIXPBX@45.58.43.180>;tag=1257665470
To: <sip:2004@45.58.32.215:10060>
Contact: <sips:ZIIXPBX@45.58.32.215:443;transport=wss>
Call-ID: 1350a8bc-b4e5-9bda-a426-1273dadecd5b
CSeq: 1714179718 INVITE
Content-Type: application/sdp
Content-Length: 1494
Max-Forwards: 70
Route: <sip:177.245.55.166:54162;transport=wss;lr>
User-Agent: webrtc2sip Media Server 2.6.0

v=0
o=doubango 1983 678901 IN IP4 45.58.32.215
s=-
c=IN IP4 45.58.32.215
t=0 0
a=acap:1 setup:actpass
a=acap:2 connection:new
a=acap:3 fingerprint:sha-256 64:5F:BD:2B:11:11:2F:65:D1:BB:6E:75:56:26:BB:89:CF:77:65:70:71:33:C9:A7:94:D1:10:1B:E0:3F:17:45
a=acap:4 fingerprint:sha-1 6F:F0:DB:E0:58:CF:F1:44:19:60:00:09:BD:B3:8E:0E:2E:4D:C1:64
a=tcap:1 UDP/TLS/RTP/SAVPF UDP/TLS/RTP/SAVP RTP/SAVPF RTP/SAVP RTP/AVPF
m=audio 50598 RTP/AVP 8 0 3 101
c=IN IP4 45.58.32.215
a=ptime:20
a=minptime:1
a=maxptime:255
a=silenceSupp:off - - - -
a=rtpmap:8 PCMA/8000/1
a=rtpmap:0 PCMU/8000/1
a=rtpmap:3 GSM/8000/1
a=rtpmap:101 telephone-event/8000/1
a=fmtp:101 0-16
a=acap:5 crypto:1 AES_CM_128_HMAC_SHA1_80 inline:BJN0ObHlDjoCfY24S3h6wALQFcK2GmS874usR/sg
a=acap:6 crypto:2 AES_CM_128_HMAC_SHA1_32 inline:08Rg307jvDsC8U8cGUxzDATeGGxYqiA84jg41RPi
a=pcfg:1 t=1 a=1,2,4|3
a=pcfg:2 t=2 a=1,2,4|3
a=pcfg:3 t=3 a=5,6
a=pcfg:4 t=4 a=5,6
a=pcfg:5 t=5
a=sendrecv
a=rtcp-mux
a=ssrc:846243228 cname:359a5bfa5516872b7f8f0b79f4a5406d
a=ssrc:846243228 mslabel:6994f7d1-6ce9-4fbd-acfd-84e5131ca2e2
a=ssrc:846243228 label:doubango@audio
a=ice-ufrag:kwID9tS4W8TOlwo
a=ice-pwd:pf2naUPN8Zh90mDmUf5t1H
a=candidate:gtkx4VOKJVRSmFb 1 udp 2130706431 45.58.32.215 50598 typ host
a=candidate:gtkx4VOKJVRSmFb 2 udp 2130706430 45.58.32.215 50599 typ host
a=candidate:dGvsJ5kK2K4CAwY 1 udp 2130706175 10.18.240.2 44664 typ host
a=candidate:dGvsJ5kK2K4CAwY 2 udp 2130706174 10.18.240.2 44665 typ host

State machine: tsip_transac_ist_Started_2_Proceeding_X_INVITE
SEND: SIP/2.0 100 Trying (sent from the Transaction Layer)
Via: SIP/2.0/WSS 45.58.32.215:443;rport=443;branch=z9hG4bK-2062457853
From: <sip:ZIIXPBX@45.58.43.180>;tag=1257665470
To: <sip:2004@45.58.32.215:10060>
Call-ID: 1350a8bc-b4e5-9bda-a426-1273dadecd5b
CSeq: 1714179718 INVITE
Content-Length: 0


ICE servers:[{"url":"stun:stun.l.google.com:19302"},{"url":"stun:stun.counterpath.net:3478"},{"url":"stun:numb.viagenie.ca:3478"}]
setRemoteDescription(offer)
v=0
o=doubango 1983 678901 IN IP4 45.58.32.215
s=-
c=IN IP4 45.58.32.215
t=0 0
a=setup:actpass
a=connection:new
a=fingerprint:sha-256 64:5F:BD:2B:11:11:2F:65:D1:BB:6E:75:56:26:BB:89:CF:77:65:70:71:33:C9:A7:94:D1:10:1B:E0:3F:17:45
a=acap:4 fingerprint:sha-1 6F:F0:DB:E0:58:CF:F1:44:19:60:00:09:BD:B3:8E:0E:2E:4D:C1:64
a=tcap:1 UDP/TLS/RTP/SAVPF UDP/TLS/RTP/SAVP RTP/SAVPF RTP/SAVP RTP/AVPF
m=audio 50598 RTP/SAVPF 8 0 3 101
c=IN IP4 45.58.32.215
a=ptime:20
a=minptime:1
a=maxptime:255
a=silenceSupp:off - - - -
a=rtpmap:8 PCMA/8000/1
a=rtpmap:0 PCMU/8000/1
a=rtpmap:3 GSM/8000/1
a=rtpmap:101 telephone-event/8000/1
a=fmtp:101 0-16
a=acap:5 crypto:1 AES_CM_128_HMAC_SHA1_80 inline:BJN0ObHlDjoCfY24S3h6wALQFcK2GmS874usR/sg
a=acap:6 crypto:2 AES_CM_128_HMAC_SHA1_32 inline:08Rg307jvDsC8U8cGUxzDATeGGxYqiA84jg41RPi
a=pcfg:1 t=1 a=1,2,4|3
a=pcfg:2 t=2 a=1,2,4|3
a=pcfg:3 t=3 a=5,6
a=pcfg:4 t=4 a=5,6
a=pcfg:5 t=5
a=sendrecv
a=rtcp-mux
a=ssrc:846243228 cname:359a5bfa5516872b7f8f0b79f4a5406d
a=ssrc:846243228 mslabel:6994f7d1-6ce9-4fbd-acfd-84e5131ca2e2
a=ssrc:846243228 label:doubango@audio
a=ice-ufrag:kwID9tS4W8TOlwo
a=ice-pwd:pf2naUPN8Zh90mDmUf5t1H
a=candidate:gtkx4VOKJVRSmFb 1 udp 2130706431 45.58.32.215 50598 typ host
a=candidate:gtkx4VOKJVRSmFb 2 udp 2130706430 45.58.32.215 50599 typ host
a=candidate:dGvsJ5kK2K4CAwY 1 udp 2130706175 10.18.240.2 44664 typ host
a=candidate:dGvsJ5kK2K4CAwY 2 udp 2130706174 10.18.240.2 44665 typ host

State machine: s0000_Started_2_Ringing_X_iINVITE
State machine: tsip_transac_ist_Proceeding_2_Proceeding_X_1xx
SEND: SIP/2.0 180 Ringing
Via: SIP/2.0/WSS 45.58.32.215:443;rport=443;branch=z9hG4bK-2062457853
From: <sip:ZIIXPBX@45.58.43.180>;tag=1257665470
To: <sip:2004@45.58.32.215:10060>;tag=gGUTSlB6hSb0Z6t12LF8
Contact: <sips:2004@df7jal23ls0d.invalid;transport=wss>
Call-ID: 1350a8bc-b4e5-9bda-a426-1273dadecd5b
CSeq: 1714179718 INVITE
Content-Length: 0
Allow: ACK, BYE, CANCEL, INVITE, MESSAGE, NOTIFY, OPTIONS, PRACK, REFER, UPDATE


State machine: s0000_Ringing_2_Connected_X_Accept
onGetUserMediaSuccess
createAnswer
onSetRemoteDescriptionSuccess
session event = connected
onCreateSdpSuccess
session event = m_stream_audio_local_added
onSignalingstateChange:have-remote-offer
onGetUserMediaSuccess
createAnswer
__on_add_stream
onNegotiationNeeded
onSetLocalDescriptionSuccess
onCreateSdpSuccess
session event = m_stream_audio_local_added
session event = m_stream_audio_remote_added
onSignalingstateChange:stable
onIceCandidate = gathering
onSetLocalDescriptionError
Failed to set local answer sdp: Called in wrong state: STATE_INPROGRESS
State machine: x0000_Any_2_Trying_X_oBYE
SEND: BYE sips:ZIIXPBX@45.58.32.215:443;transport=wss SIP/2.0
Via: SIP/2.0/WSS df7jal23ls0d.invalid;branch=z9hG4bKZcsEhSsbATQllxa1rCxe8wTt4LVl5C76;rport
From: <sip:2004@45.58.32.215:10060>;tag=gGUTSlB6hSb0Z6t12LF8
To: <sip:ZIIXPBX@45.58.43.180>;tag=1257665470
Call-ID: 1350a8bc-b4e5-9bda-a426-1273dadecd5b
CSeq: 37866 BYE
Content-Length: 0
Route: <sip:lab.ziix.mx:5060;lr;sipml5-outbound;transport=udp>
Max-Forwards: 70
User-Agent: IM-client/OMA1.0 sipML5-v1.0.0.0
Organization: Doubango Telecom


session event = terminating
__tsip_transport_ws_onmessage
recv=SIP/2.0 200 OK
Via: SIP/2.0/WSS df7jal23ls0d.invalid;rport;branch=z9hG4bKZcsEhSsbATQllxa1rCxe8wTt4LVl5C76
From: <sip:2004@45.58.32.215:10060>;tag=gGUTSlB6hSb0Z6t12LF8
To: <sip:ZIIXPBX@45.58.43.180>;tag=1257665470
Contact: <sips:ZIIXPBX@45.58.32.215:443;transport=wss;ws-src-ip=177.245.55.166;ws-src-port=54162;ws-src-proto=wss>
Call-ID: 1350a8bc-b4e5-9bda-a426-1273dadecd5b
CSeq: 37866 BYE
Content-Length: 0


State machine: x0000_Any_2_Terminated_X_i2xxBYE
=== INVITE Dialog terminated ===
TypeError: this.o_local_stream.stop is not a function(…)
onIceCandidate = complete
ICE GATHERING COMPLETED!
onIceGatheringCompleted
onNegotiationNeeded
onGetUserMediaSuccess
onGetUserMediaSuccess but no local sdp request is pending
onIceCandidate = complete
ICE GATHERING COMPLETED!
onIceGatheringCompleted
onIceGatheringCompleted but no local sdp request is pending
onIceCandidate = complete
ICE GATHERING COMPLETED!
onIceGatheringCompleted
onIceGatheringCompleted but no local sdp request is pending
State machine: tsip_transac_ist_Proceeding_2_Accepted_X_2xx
SEND: SIP/2.0 200 OK
Via: SIP/2.0/WSS 45.58.32.215:443;rport=443;branch=z9hG4bK-2062457853
From: <sip:ZIIXPBX@45.58.43.180>;tag=1257665470
To: <sip:2004@45.58.32.215:10060>;tag=gGUTSlB6hSb0Z6t12LF8
Contact: <sips:2004@df7jal23ls0d.invalid;transport=wss>
Call-ID: 1350a8bc-b4e5-9bda-a426-1273dadecd5b
CSeq: 1714179718 INVITE
Content-Type: application/sdp
Content-Length: 1111
Allow: ACK, BYE, CANCEL, INVITE, MESSAGE, NOTIFY, OPTIONS, PRACK, REFER, UPDATE

v=0
o=- 7879262369114788000 2 IN IP4 127.0.0.1
s=Doubango Telecom - chrome
t=0 0
a=msid-semantic: WMS onX93V4s41wwWjKpVckmI9EB4nDA2jRkBzcq
m=audio 55365 UDP/TLS/RTP/SAVPF 8 0 101
c=IN IP4 177.245.55.166
a=rtcp:9 IN IP4 0.0.0.0
a=candidate:2880323124 1 udp 2122260223 192.168.1.116 55365 typ host generation 0
a=candidate:3844981444 1 tcp 1518280447 192.168.1.116 0 typ host tcptype active generation 0
a=candidate:719730816 1 udp 1686052607 177.245.55.166 55365 typ srflx raddr 192.168.1.116 rport 55365 generation 0
a=ice-ufrag:sDQ1NCPVItRZXB9e
a=ice-pwd:IRAaTIK1qrhc6fx4lRr5IV4e
a=fingerprint:sha-256 1C:40:DE:BB:A9:76:49:F0:1D:72:B7:05:FD:D0:F0:2F:8A:9B:74:55:55:12:A6:7E:32:09:DD:35:93:0C:73:6E
a=setup:active
a=mid:audio
a=sendrecv
a=rtcp-mux
a=rtpmap:8 PCMA/8000
a=rtpmap:0 PCMU/8000
a=rtpmap:101 telephone-event/8000
a=ssrc:2793257514 cname:V3K9fiVc398M3PbC
a=ssrc:2793257514 msid:onX93V4s41wwWjKpVckmI9EB4nDA2jRkBzcq a945a5ea-3a23-4e53-8cd1-f57f114457c7
a=ssrc:2793257514 mslabel:onX93V4s41wwWjKpVckmI9EB4nDA2jRkBzcq
a=ssrc:2793257514 label:a945a5ea-3a23-4e53-8cd1-f57f114457c7

__tsip_transport_ws_onmessage
recv=ACK sip:2004@45.58.32.215:10060;rtcweb-breaker=yes;transport=udp;ws-src-ip=177.245.55.166;ws-src-port=54162;ws-src-proto=wss SIP/2.0
Via: SIP/2.0/UDP 45.58.43.180:5060;rport=5060;received=45.58.43.180;branch=z9hG4bK5019f7a5
From: "ZIIX-PBX"<sip:ZIIXPBX@45.58.43.180>;tag=as07bdc76e
To: <sip:2004@45.58.32.215:10060;rtcweb-breaker=yes;transport=udp;ws-src-ip=177.245.55.166;ws-src-port=54162;ws-src-proto=wss>;tag=1211037198
Contact: <sip:ZIIXPBX@45.58.43.180>
Call-ID: 49a531196f15671a7c04792e314f0668@45.58.43.180
CSeq: 102 ACK
Content-Length: 0
User-Agent: Asterisk PBX
Max-Forwards: 70


SEND: SIP/2.0 481 Dialog/Transaction Does Not Exist
Via: SIP/2.0/UDP 45.58.43.180:5060;rport=5060;received=45.58.43.180;branch=z9hG4bK5019f7a5
From: "ZIIX-PBX"<sip:ZIIXPBX@45.58.43.180>;tag=as07bdc76e
To: <sip:2004@45.58.32.215:10060;rtcweb-breaker=yes;transport=udp;ws-src-ip=177.245.55.166;ws-src-port=54162;ws-src-proto=wss>;tag=1211037198
Call-ID: 49a531196f15671a7c04792e314f0668@45.58.43.180
CSeq: 102 ACK
Content-Length: 0


State machine: tsip_transac_ist_Accepted_2_Accepted_timerX
SEND: SIP/2.0 200 OK
Via: SIP/2.0/WSS 45.58.32.215:443;rport=443;branch=z9hG4bK-2062457853
From: <sip:ZIIXPBX@45.58.43.180>;tag=1257665470
To: <sip:2004@45.58.32.215:10060>;tag=gGUTSlB6hSb0Z6t12LF8
Contact: <sips:2004@df7jal23ls0d.invalid;transport=wss>
Call-ID: 1350a8bc-b4e5-9bda-a426-1273dadecd5b
CSeq: 1714179718 INVITE
Content-Type: application/sdp
Content-Length: 1111
Allow: ACK, BYE, CANCEL, INVITE, MESSAGE, NOTIFY, OPTIONS, PRACK, REFER, UPDATE

v=0
o=- 7879262369114788000 2 IN IP4 127.0.0.1
s=Doubango Telecom - chrome
t=0 0
a=msid-semantic: WMS onX93V4s41wwWjKpVckmI9EB4nDA2jRkBzcq
m=audio 55365 UDP/TLS/RTP/SAVPF 8 0 101
c=IN IP4 177.245.55.166
a=rtcp:9 IN IP4 0.0.0.0
a=candidate:2880323124 1 udp 2122260223 192.168.1.116 55365 typ host generation 0
a=candidate:3844981444 1 tcp 1518280447 192.168.1.116 0 typ host tcptype active generation 0
a=candidate:719730816 1 udp 1686052607 177.245.55.166 55365 typ srflx raddr 192.168.1.116 rport 55365 generation 0
a=ice-ufrag:sDQ1NCPVItRZXB9e
a=ice-pwd:IRAaTIK1qrhc6fx4lRr5IV4e
a=fingerprint:sha-256 1C:40:DE:BB:A9:76:49:F0:1D:72:B7:05:FD:D0:F0:2F:8A:9B:74:55:55:12:A6:7E:32:09:DD:35:93:0C:73:6E
a=setup:active
a=mid:audio
a=sendrecv
a=rtcp-mux
a=rtpmap:8 PCMA/8000
a=rtpmap:0 PCMU/8000
a=rtpmap:101 telephone-event/8000
a=ssrc:2793257514 cname:V3K9fiVc398M3PbC
a=ssrc:2793257514 msid:onX93V4s41wwWjKpVckmI9EB4nDA2jRkBzcq a945a5ea-3a23-4e53-8cd1-f57f114457c7
a=ssrc:2793257514 mslabel:onX93V4s41wwWjKpVckmI9EB4nDA2jRkBzcq
a=ssrc:2793257514 label:a945a5ea-3a23-4e53-8cd1-f57f114457c7

State machine: tsip_transac_ist_Accepted_2_Accepted_timerX
SEND: SIP/2.0 200 OK
Via: SIP/2.0/WSS 45.58.32.215:443;rport=443;branch=z9hG4bK-2062457853
From: <sip:ZIIXPBX@45.58.43.180>;tag=1257665470
To: <sip:2004@45.58.32.215:10060>;tag=gGUTSlB6hSb0Z6t12LF8
Contact: <sips:2004@df7jal23ls0d.invalid;transport=wss>
Call-ID: 1350a8bc-b4e5-9bda-a426-1273dadecd5b
CSeq: 1714179718 INVITE
Content-Type: application/sdp
Content-Length: 1111
Allow: ACK, BYE, CANCEL, INVITE, MESSAGE, NOTIFY, OPTIONS, PRACK, REFER, UPDATE

v=0
o=- 7879262369114788000 2 IN IP4 127.0.0.1
s=Doubango Telecom - chrome
t=0 0
a=msid-semantic: WMS onX93V4s41wwWjKpVckmI9EB4nDA2jRkBzcq
m=audio 55365 UDP/TLS/RTP/SAVPF 8 0 101
c=IN IP4 177.245.55.166
a=rtcp:9 IN IP4 0.0.0.0
a=candidate:2880323124 1 udp 2122260223 192.168.1.116 55365 typ host generation 0
a=candidate:3844981444 1 tcp 1518280447 192.168.1.116 0 typ host tcptype active generation 0
a=candidate:719730816 1 udp 1686052607 177.245.55.166 55365 typ srflx raddr 192.168.1.116 rport 55365 generation 0
a=ice-ufrag:sDQ1NCPVItRZXB9e
a=ice-pwd:IRAaTIK1qrhc6fx4lRr5IV4e
a=fingerprint:sha-256 1C:40:DE:BB:A9:76:49:F0:1D:72:B7:05:FD:D0:F0:2F:8A:9B:74:55:55:12:A6:7E:32:09:DD:35:93:0C:73:6E
a=setup:active
a=mid:audio
a=sendrecv
a=rtcp-mux
a=rtpmap:8 PCMA/8000
a=rtpmap:0 PCMU/8000
a=rtpmap:101 telephone-event/8000
a=ssrc:2793257514 cname:V3K9fiVc398M3PbC
a=ssrc:2793257514 msid:onX93V4s41wwWjKpVckmI9EB4nDA2jRkBzcq a945a5ea-3a23-4e53-8cd1-f57f114457c7
a=ssrc:2793257514 mslabel:onX93V4s41wwWjKpVckmI9EB4nDA2jRkBzcq
a=ssrc:2793257514 label:a945a5ea-3a23-4e53-8cd1-f57f114457c7

State machine: tsip_transac_ist_Accepted_2_Accepted_timerX
SEND: SIP/2.0 200 OK
Via: SIP/2.0/WSS 45.58.32.215:443;rport=443;branch=z9hG4bK-2062457853
From: <sip:ZIIXPBX@45.58.43.180>;tag=1257665470
To: <sip:2004@45.58.32.215:10060>;tag=gGUTSlB6hSb0Z6t12LF8
Contact: <sips:2004@df7jal23ls0d.invalid;transport=wss>
Call-ID: 1350a8bc-b4e5-9bda-a426-1273dadecd5b
CSeq: 1714179718 INVITE
Content-Type: application/sdp
Content-Length: 1111
Allow: ACK, BYE, CANCEL, INVITE, MESSAGE, NOTIFY, OPTIONS, PRACK, REFER, UPDATE

v=0
o=- 7879262369114788000 2 IN IP4 127.0.0.1
s=Doubango Telecom - chrome
t=0 0
a=msid-semantic: WMS onX93V4s41wwWjKpVckmI9EB4nDA2jRkBzcq
m=audio 55365 UDP/TLS/RTP/SAVPF 8 0 101
c=IN IP4 177.245.55.166
a=rtcp:9 IN IP4 0.0.0.0
a=candidate:2880323124 1 udp 2122260223 192.168.1.116 55365 typ host generation 0
a=candidate:3844981444 1 tcp 1518280447 192.168.1.116 0 typ host tcptype active generation 0
a=candidate:719730816 1 udp 1686052607 177.245.55.166 55365 typ srflx raddr 192.168.1.116 rport 55365 generation 0
a=ice-ufrag:sDQ1NCPVItRZXB9e
a=ice-pwd:IRAaTIK1qrhc6fx4lRr5IV4e
a=fingerprint:sha-256 1C:40:DE:BB:A9:76:49:F0:1D:72:B7:05:FD:D0:F0:2F:8A:9B:74:55:55:12:A6:7E:32:09:DD:35:93:0C:73:6E
a=setup:active
a=mid:audio
a=sendrecv
a=rtcp-mux
a=rtpmap:8 PCMA/8000
a=rtpmap:0 PCMU/8000
a=rtpmap:101 telephone-event/8000
a=ssrc:2793257514 cname:V3K9fiVc398M3PbC
a=ssrc:2793257514 msid:onX93V4s41wwWjKpVckmI9EB4nDA2jRkBzcq a945a5ea-3a23-4e53-8cd1-f57f114457c7
a=ssrc:2793257514 mslabel:onX93V4s41wwWjKpVckmI9EB4nDA2jRkBzcq
a=ssrc:2793257514 label:a945a5ea-3a23-4e53-8cd1-f57f114457c7

The FSM is in the final state
State machine: tsip_transac_ist_Accepted_2_Accepted_timerX
SEND: SIP/2.0 200 OK
Via: SIP/2.0/WSS 45.58.32.215:443;rport=443;branch=z9hG4bK-2062457853
From: <sip:ZIIXPBX@45.58.43.180>;tag=1257665470
To: <sip:2004@45.58.32.215:10060>;tag=gGUTSlB6hSb0Z6t12LF8
Contact: <sips:2004@df7jal23ls0d.invalid;transport=wss>
Call-ID: 1350a8bc-b4e5-9bda-a426-1273dadecd5b
CSeq: 1714179718 INVITE
Content-Type: application/sdp
Content-Length: 1111
Allow: ACK, BYE, CANCEL, INVITE, MESSAGE, NOTIFY, OPTIONS, PRACK, REFER, UPDATE

v=0
o=- 7879262369114788000 2 IN IP4 127.0.0.1
s=Doubango Telecom - chrome
t=0 0
a=msid-semantic: WMS onX93V4s41wwWjKpVckmI9EB4nDA2jRkBzcq
m=audio 55365 UDP/TLS/RTP/SAVPF 8 0 101
c=IN IP4 177.245.55.166
a=rtcp:9 IN IP4 0.0.0.0
a=candidate:2880323124 1 udp 2122260223 192.168.1.116 55365 typ host generation 0
a=candidate:3844981444 1 tcp 1518280447 192.168.1.116 0 typ host tcptype active generation 0
a=candidate:719730816 1 udp 1686052607 177.245.55.166 55365 typ srflx raddr 192.168.1.116 rport 55365 generation 0
a=ice-ufrag:sDQ1NCPVItRZXB9e
a=ice-pwd:IRAaTIK1qrhc6fx4lRr5IV4e
a=fingerprint:sha-256 1C:40:DE:BB:A9:76:49:F0:1D:72:B7:05:FD:D0:F0:2F:8A:9B:74:55:55:12:A6:7E:32:09:DD:35:93:0C:73:6E
a=setup:active
a=mid:audio
a=sendrecv
a=rtcp-mux
a=rtpmap:8 PCMA/8000
a=rtpmap:0 PCMU/8000
a=rtpmap:101 telephone-event/8000
a=ssrc:2793257514 cname:V3K9fiVc398M3PbC
a=ssrc:2793257514 msid:onX93V4s41wwWjKpVckmI9EB4nDA2jRkBzcq a945a5ea-3a23-4e53-8cd1-f57f114457c7
a=ssrc:2793257514 mslabel:onX93V4s41wwWjKpVckmI9EB4nDA2jRkBzcq
a=ssrc:2793257514 label:a945a5ea-3a23-4e53-8cd1-f57f114457c7

State machine: tsip_transac_ist_Accepted_2_Accepted_timerX
SEND: SIP/2.0 200 OK
Via: SIP/2.0/WSS 45.58.32.215:443;rport=443;branch=z9hG4bK-2062457853
From: <sip:ZIIXPBX@45.58.43.180>;tag=1257665470
To: <sip:2004@45.58.32.215:10060>;tag=gGUTSlB6hSb0Z6t12LF8
Contact: <sips:2004@df7jal23ls0d.invalid;transport=wss>
Call-ID: 1350a8bc-b4e5-9bda-a426-1273dadecd5b
CSeq: 1714179718 INVITE
Content-Type: application/sdp
Content-Length: 1111
Allow: ACK, BYE, CANCEL, INVITE, MESSAGE, NOTIFY, OPTIONS, PRACK, REFER, UPDATE

v=0
o=- 7879262369114788000 2 IN IP4 127.0.0.1
s=Doubango Telecom - chrome
t=0 0
a=msid-semantic: WMS onX93V4s41wwWjKpVckmI9EB4nDA2jRkBzcq
m=audio 55365 UDP/TLS/RTP/SAVPF 8 0 101
c=IN IP4 177.245.55.166
a=rtcp:9 IN IP4 0.0.0.0
a=candidate:2880323124 1 udp 2122260223 192.168.1.116 55365 typ host generation 0
a=candidate:3844981444 1 tcp 1518280447 192.168.1.116 0 typ host tcptype active generation 0
a=candidate:719730816 1 udp 1686052607 177.245.55.166 55365 typ srflx raddr 192.168.1.116 rport 55365 generation 0
a=ice-ufrag:sDQ1NCPVItRZXB9e
a=ice-pwd:IRAaTIK1qrhc6fx4lRr5IV4e
a=fingerprint:sha-256 1C:40:DE:BB:A9:76:49:F0:1D:72:B7:05:FD:D0:F0:2F:8A:9B:74:55:55:12:A6:7E:32:09:DD:35:93:0C:73:6E
a=setup:active
a=mid:audio
a=sendrecv
a=rtcp-mux
a=rtpmap:8 PCMA/8000
a=rtpmap:0 PCMU/8000
a=rtpmap:101 telephone-event/8000
a=ssrc:2793257514 cname:V3K9fiVc398M3PbC
a=ssrc:2793257514 msid:onX93V4s41wwWjKpVckmI9EB4nDA2jRkBzcq a945a5ea-3a23-4e53-8cd1-f57f114457c7
a=ssrc:2793257514 mslabel:onX93V4s41wwWjKpVckmI9EB4nDA2jRkBzcq
a=ssrc:2793257514 label:a945a5ea-3a23-4e53-8cd1-f57f114457c7

State machine: tsip_transac_ist_Accepted_2_Terminated_timerL
