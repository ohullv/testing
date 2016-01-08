__tsip_transport_ws_onmessage
recv=INVITE sip:2004@45.58.32.215:10060 SIP/2.0
Via: SIP/2.0/WSS 45.58.32.215:443;rport;branch=z9hG4bK-1502136829
From: <sip:ZIIXPBX@45.58.43.180>;tag=1733417987
To: <sip:2004@45.58.32.215:10060>
Contact: <sips:ZIIXPBX@45.58.32.215:443;transport=wss>
Call-ID: 75167414-413a-8dea-f58b-aa998bee0262
CSeq: 1663060673 INVITE
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
m=audio 49486 RTP/AVP 8 0 3 101
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
a=acap:5 crypto:1 AES_CM_128_HMAC_SHA1_80 inline:Dfx6y08o8mOhvveZ1fzfmhP5lHeDtLWoQ4LcYW0t
a=acap:6 crypto:2 AES_CM_128_HMAC_SHA1_32 inline:0WYZ5mNcux+n5CJ7Dxe3PufnlnJ/NsgSV9MoKz9g
a=pcfg:1 t=1 a=1,2,4|3
a=pcfg:2 t=2 a=1,2,4|3
a=pcfg:3 t=3 a=5,6
a=pcfg:4 t=4 a=5,6
a=pcfg:5 t=5
a=sendrecv
a=rtcp-mux
a=ssrc:585918093 cname:6806317b4cbf2dc9c80faf6376fb993e
a=ssrc:585918093 mslabel:6994f7d1-6ce9-4fbd-acfd-84e5131ca2e2
a=ssrc:585918093 label:doubango@audio
a=ice-ufrag:yCMtsHGbDOdp0EN
a=ice-pwd:B1xDpk7vgVVH8JuwMMm6o8
a=candidate:tr6crN5tP1gVwaH 1 udp 2130706431 45.58.32.215 49486 typ host
a=candidate:tr6crN5tP1gVwaH 2 udp 2130706430 45.58.32.215 49487 typ host
a=candidate:3bsg2KyRkvSlse3 1 udp 2130706175 10.18.240.2 50996 typ host
a=candidate:3bsg2KyRkvSlse3 2 udp 2130706174 10.18.240.2 50997 typ host

State machine: tsip_transac_ist_Started_2_Proceeding_X_INVITE
SEND: SIP/2.0 100 Trying (sent from the Transaction Layer)
Via: SIP/2.0/WSS 45.58.32.215:443;rport=443;branch=z9hG4bK-1502136829
From: <sip:ZIIXPBX@45.58.43.180>;tag=1733417987
To: <sip:2004@45.58.32.215:10060>
Call-ID: 75167414-413a-8dea-f58b-aa998bee0262
CSeq: 1663060673 INVITE
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
m=audio 49486 RTP/SAVPF 8 0 3 101
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
a=acap:5 crypto:1 AES_CM_128_HMAC_SHA1_80 inline:Dfx6y08o8mOhvveZ1fzfmhP5lHeDtLWoQ4LcYW0t
a=acap:6 crypto:2 AES_CM_128_HMAC_SHA1_32 inline:0WYZ5mNcux+n5CJ7Dxe3PufnlnJ/NsgSV9MoKz9g
a=pcfg:1 t=1 a=1,2,4|3
a=pcfg:2 t=2 a=1,2,4|3
a=pcfg:3 t=3 a=5,6
a=pcfg:4 t=4 a=5,6
a=pcfg:5 t=5
a=sendrecv
a=rtcp-mux
a=ssrc:585918093 cname:6806317b4cbf2dc9c80faf6376fb993e
a=ssrc:585918093 mslabel:6994f7d1-6ce9-4fbd-acfd-84e5131ca2e2
a=ssrc:585918093 label:doubango@audio
a=ice-ufrag:yCMtsHGbDOdp0EN
a=ice-pwd:B1xDpk7vgVVH8JuwMMm6o8
a=candidate:tr6crN5tP1gVwaH 1 udp 2130706431 45.58.32.215 49486 typ host
a=candidate:tr6crN5tP1gVwaH 2 udp 2130706430 45.58.32.215 49487 typ host
a=candidate:3bsg2KyRkvSlse3 1 udp 2130706175 10.18.240.2 50996 typ host
a=candidate:3bsg2KyRkvSlse3 2 udp 2130706174 10.18.240.2 50997 typ host

State machine: s0000_Started_2_Ringing_X_iINVITE
State machine: tsip_transac_ist_Proceeding_2_Proceeding_X_1xx
SEND: SIP/2.0 180 Ringing
Via: SIP/2.0/WSS 45.58.32.215:443;rport=443;branch=z9hG4bK-1502136829
From: <sip:ZIIXPBX@45.58.43.180>;tag=1733417987
To: <sip:2004@45.58.32.215:10060>;tag=KEnoTAUKITciKRouwDGw
Contact: <sips:2004@df7jal23ls0d.invalid;transport=wss>
Call-ID: 75167414-413a-8dea-f58b-aa998bee0262
CSeq: 1663060673 INVITE
Content-Length: 0
Allow: ACK, BYE, CANCEL, INVITE, MESSAGE, NOTIFY, OPTIONS, PRACK, REFER, UPDATE


State machine: s0000_Ringing_2_Connected_X_Accept
session event = connected
onSignalingstateChange:have-remote-offer
onSetRemoteDescriptionSuccess
__on_add_stream
session event = m_stream_audio_remote_added
onGetUserMediaSuccess
createAnswer
onCreateSdpSuccess
session event = m_stream_audio_local_added
onNegotiationNeeded
onSignalingstateChange:stable
onSetLocalDescriptionSuccess
onIceCandidate = gathering
onIceCandidate = complete
ICE GATHERING COMPLETED!
onIceGatheringCompleted
State machine: tsip_transac_ist_Proceeding_2_Accepted_X_2xx
SEND: SIP/2.0 200 OK
Via: SIP/2.0/WSS 45.58.32.215:443;rport=443;branch=z9hG4bK-1502136829
From: <sip:ZIIXPBX@45.58.43.180>;tag=1733417987
To: <sip:2004@45.58.32.215:10060>;tag=KEnoTAUKITciKRouwDGw
Contact: <sips:2004@df7jal23ls0d.invalid;transport=wss>
Call-ID: 75167414-413a-8dea-f58b-aa998bee0262
CSeq: 1663060673 INVITE
Content-Type: application/sdp
Content-Length: 1107
Allow: ACK, BYE, CANCEL, INVITE, MESSAGE, NOTIFY, OPTIONS, PRACK, REFER, UPDATE

v=0
o=- 5912035002791490000 2 IN IP4 127.0.0.1
s=Doubango Telecom - chrome
t=0 0
a=msid-semantic: WMS Vrrk66aWQNMan5KitU2S8dRPwEqgbrccbb6O
m=audio 63045 UDP/TLS/RTP/SAVPF 8 0 101
c=IN IP4 177.245.55.166
a=rtcp:9 IN IP4 0.0.0.0
a=candidate:2880323124 1 udp 2122260223 192.168.1.116 63045 typ host generation 0
a=candidate:719730816 1 udp 1686052607 177.245.55.166 63045 typ srflx raddr 192.168.1.116 rport 63045 generation 0
a=candidate:3844981444 1 tcp 1518280447 192.168.1.116 0 typ host tcptype active generation 0
a=ice-ufrag:x2onGpKZ4SGsBYrY
a=ice-pwd:SY3LOZbJtPcDbsLUVgjdRsD5
a=fingerprint:sha-256 1C:40:DE:BB:A9:76:49:F0:1D:72:B7:05:FD:D0:F0:2F:8A:9B:74:55:55:12:A6:7E:32:09:DD:35:93:0C:73:6E
a=setup:active
a=mid:audio
a=sendrecv
a=rtcp-mux
a=rtpmap:8 PCMA/8000
a=rtpmap:0 PCMU/8000
a=rtpmap:101 telephone-event/8000
a=ssrc:397217779 cname:Rvng4eGh1gCmFuMa
a=ssrc:397217779 msid:Vrrk66aWQNMan5KitU2S8dRPwEqgbrccbb6O 57ff32de-c03a-4f70-a1a9-27b91e6d3704
a=ssrc:397217779 mslabel:Vrrk66aWQNMan5KitU2S8dRPwEqgbrccbb6O
a=ssrc:397217779 label:57ff32de-c03a-4f70-a1a9-27b91e6d3704

__tsip_transport_ws_onmessage
recv=ACK sips:2004@df7jal23ls0d.invalid;transport=wss SIP/2.0
Via: SIP/2.0/WSS 45.58.32.215:443;rport;branch=z9hG4bK-388530695
From: <sip:ZIIXPBX@45.58.43.180>;tag=1733417987
To: <sip:2004@45.58.32.215:10060>;tag=KEnoTAUKITciKRouwDGw
Contact: <sips:ZIIXPBX@45.58.32.215:443;transport=wss>
Call-ID: 75167414-413a-8dea-f58b-aa998bee0262
CSeq: 1663060673 ACK
Content-Length: 0
Max-Forwards: 70
Route: <sip:177.245.55.166:54162;transport=wss;lr>
User-Agent: webrtc2sip Media Server 2.6.0


State machine: tsip_transac_ist_Accepted_2_Accepted_iACK
State machine: x0000_Connected_2_Connected_X_iACK
call:event -> [object Object]
tagging:new -> [object Object]
Mixed Content: The page at 'https://lab.ziix.mx/#/' was loaded over HTTPS, but requested an insecure resource 'http://www.righttech.mx/'. This request has been blocked; the content must be served over HTTPS.
State machine: x0000_Any_2_Trying_X_oBYE
SEND: BYE sips:ZIIXPBX@45.58.32.215:443;transport=wss SIP/2.0
Via: SIP/2.0/WSS df7jal23ls0d.invalid;branch=z9hG4bKIUhzkk27dfAl8XebWNTCoq2mhJmU6B7L;rport
From: <sip:2004@45.58.32.215:10060>;tag=KEnoTAUKITciKRouwDGw
To: <sip:ZIIXPBX@45.58.43.180>;tag=1733417987
Call-ID: 75167414-413a-8dea-f58b-aa998bee0262
CSeq: 50305 BYE
Content-Length: 0
Route: <sip:lab.ziix.mx:5060;lr;sipml5-outbound;transport=udp>
Max-Forwards: 70
User-Agent: IM-client/OMA1.0 sipML5-v1.0.0.0
Organization: Doubango Telecom


TypeError: this.o_local_stream.stop is not a function(…)
=== INVITE Dialog terminated ===
TypeError: this.o_local_stream.stop is not a function
    at tmedia_session_jsep.close (SIPml-api.js:3)
    at tmedia_session_jsep.__stop (SIPml-api.js:1)
    at tmedia_session.stop (SIPml-api.js:1)
    at tmedia_session_mgr.stop (SIPml-api.js:1)
    at tsk_fsm.__tsip_dialog_invite_onterm [as fn_onterm] (SIPml-api.js:3)
    at tsk_fsm.act (SIPml-api.js:1)
    at tsip_dialog.fsm_act (SIPml-api.js:3)
    at tsip_dialog.hangup (SIPml-api.js:3)
    at tsip_session.__action_handle (SIPml-api.js:3)
    at tsip_session.__action_any (SIPml-api.js:3)
session event = terminating
__tsip_transport_ws_onmessage
recv=SIP/2.0 200 OK
Via: SIP/2.0/WSS df7jal23ls0d.invalid;rport;branch=z9hG4bKIUhzkk27dfAl8XebWNTCoq2mhJmU6B7L
From: <sip:2004@45.58.32.215:10060>;tag=KEnoTAUKITciKRouwDGw
To: <sip:ZIIXPBX@45.58.43.180>;tag=1733417987
Contact: <sips:ZIIXPBX@45.58.32.215:443;transport=wss;ws-src-ip=177.245.55.166;ws-src-port=54162;ws-src-proto=wss>
Call-ID: 75167414-413a-8dea-f58b-aa998bee0262
CSeq: 50305 BYE
Content-Length: 0


The FSM is in the final state
onNegotiationNeeded
onGetUserMediaSuccess
onGetUserMediaSuccess but no local sdp request is pending
call:event -> [object Object]
State machine: tsip_transac_ist_Accepted_2_Terminated_timerL
