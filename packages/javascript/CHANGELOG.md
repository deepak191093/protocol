# @livekit/protocol

## 1.39.3

### Patch Changes

- normalize common os names - [#1118](https://github.com/livekit/protocol/pull/1118) ([@paulwe](https://github.com/paulwe))

- Add client info case for ESP32 - [#1113](https://github.com/livekit/protocol/pull/1113) ([@ladvoc](https://github.com/ladvoc))

## 1.39.2

### Patch Changes

- Add id field to SessionDescription message - [#1105](https://github.com/livekit/protocol/pull/1105) ([@lukasIO](https://github.com/lukasIO))

## 1.39.1

### Patch Changes

- E2E reliability for data channel - [#1099](https://github.com/livekit/protocol/pull/1099) ([@cnderrauber](https://github.com/cnderrauber))

- WHIP internal signalling to be able to support WHIP in OSS. - [#1091](https://github.com/livekit/protocol/pull/1091) ([@boks1971](https://github.com/boks1971))

## 1.39.0

### Minor Changes

- Add destination_country field to CreateSIPParticipant - [#1084](https://github.com/livekit/protocol/pull/1084) ([@biglittlebigben](https://github.com/biglittlebigben))

### Patch Changes

- merge deferred log fields - [#1070](https://github.com/livekit/protocol/pull/1070) ([@paulwe](https://github.com/paulwe))

- add agent jwt helper - [#1075](https://github.com/livekit/protocol/pull/1075) ([@paulwe](https://github.com/paulwe))

- add terminate to agent AvailabilityResponse - [#1088](https://github.com/livekit/protocol/pull/1088) ([@paulwe](https://github.com/paulwe))

- remove agent token - [#1077](https://github.com/livekit/protocol/pull/1077) ([@paulwe](https://github.com/paulwe))

- Add a MEDIA_FAILURE disconnect reason. - [#1085](https://github.com/livekit/protocol/pull/1085) ([@dennwc](https://github.com/dennwc))

- Allow updating trunk destination country - [#1087](https://github.com/livekit/protocol/pull/1087) ([@biglittlebigben](https://github.com/biglittlebigben))

- update mageutil for license - [#1068](https://github.com/livekit/protocol/pull/1068) ([@paulwe](https://github.com/paulwe))

- Add SIPTransferInfo to analytics - [#1063](https://github.com/livekit/protocol/pull/1063) ([@biglittlebigben](https://github.com/biglittlebigben))

- This adds a transfer_id as an easier to implement way to deduplicate transfer requests. It also adds a transfer_status to indicate if the event is for the start of end of a transfer, and if it's been successful. - [#1072](https://github.com/livekit/protocol/pull/1072) ([@biglittlebigben](https://github.com/biglittlebigben))

## 1.38.0

### Minor Changes

- feat: MoveParticipant API - [#1065](https://github.com/livekit/protocol/pull/1065) ([@cnderrauber](https://github.com/cnderrauber))

### Patch Changes

- fix memory path for cgroups v2 - [#1060](https://github.com/livekit/protocol/pull/1060) ([@boks1971](https://github.com/boks1971))

- Fix paths and simplify. - [#1062](https://github.com/livekit/protocol/pull/1062) ([@boks1971](https://github.com/boks1971))

## 1.37.1

### Patch Changes

- allow rewriting deferred logger values - [#1053](https://github.com/livekit/protocol/pull/1053) ([@paulwe](https://github.com/paulwe))

- Deprecate explicit AddTrackRequest fields that can be read from AudioTrackFeatures - [#1058](https://github.com/livekit/protocol/pull/1058) ([@lukasIO](https://github.com/lukasIO))

- Add PreconnectBuffer to AudioTrackFeatures, add AudioTrackFeatures to AddTrackRequest - [#1057](https://github.com/livekit/protocol/pull/1057) ([@lukasIO](https://github.com/lukasIO))

## 1.37.0

### Minor Changes

- Allow specifying extra webhooks in egress start requests - [#1040](https://github.com/livekit/protocol/pull/1040) ([@biglittlebigben](https://github.com/biglittlebigben))

- Allow updating SIP media encryption. - [#1047](https://github.com/livekit/protocol/pull/1047) ([@dennwc](https://github.com/dennwc))

- Add timeout parameter to SIP transfer API. - [#1036](https://github.com/livekit/protocol/pull/1036) ([@dennwc](https://github.com/dennwc))

### Patch Changes

- allow calling promise.Resolve more than once - [#1035](https://github.com/livekit/protocol/pull/1035) ([@paulwe](https://github.com/paulwe))

- Add CONNECTION_TIMEOUT disconnect reason - [#1037](https://github.com/livekit/protocol/pull/1037) ([@boks1971](https://github.com/boks1971))

- Add IMAGE_SUFFIX_NONE_OVERWRITE - [#1052](https://github.com/livekit/protocol/pull/1052) ([@biglittlebigben](https://github.com/biglittlebigben))

- Add rate for memory use and total. - [#1030](https://github.com/livekit/protocol/pull/1030) ([@boks1971](https://github.com/boks1971))

- Add IngressID and ResourceID attributes for the ingress participants - [#1042](https://github.com/livekit/protocol/pull/1042) ([@biglittlebigben](https://github.com/biglittlebigben))

- Revert cid changes. - [#1029](https://github.com/livekit/protocol/pull/1029) ([@boks1971](https://github.com/boks1971))

- Export GetEgressNotifyOptions - [#1045](https://github.com/livekit/protocol/pull/1045) ([@biglittlebigben](https://github.com/biglittlebigben))

- Add more fields to CodecInfo. - [#1024](https://github.com/livekit/protocol/pull/1024) ([@boks1971](https://github.com/boks1971))

- Add client info enum value for unreal - [#1032](https://github.com/livekit/protocol/pull/1032) ([@bcherry](https://github.com/bcherry))

## 1.36.1

### Patch Changes

- Refine backup codec policy - [#1022](https://github.com/livekit/protocol/pull/1022) ([@cnderrauber](https://github.com/cnderrauber))

## 1.36.0

### Minor Changes

- add cloud agents - [#1010](https://github.com/livekit/protocol/pull/1010) ([@real-danm](https://github.com/real-danm))

- Update API for SIP. - [#869](https://github.com/livekit/protocol/pull/869) ([@dennwc](https://github.com/dennwc))

### Patch Changes

- Add KindDetails enum on ParticipantInfo - [#1019](https://github.com/livekit/protocol/pull/1019) ([@lukasIO](https://github.com/lukasIO))

## 1.35.0

### Minor Changes

- Add ForwardParticipant to room service - [#1011](https://github.com/livekit/protocol/pull/1011) ([@cnderrauber](https://github.com/cnderrauber))

- Move SIP call dispatch info into s separate type. - [#989](https://github.com/livekit/protocol/pull/989) ([@dennwc](https://github.com/dennwc))

- Handle SIP hostname in address filters. Expose attribute. - [#987](https://github.com/livekit/protocol/pull/987) ([@dennwc](https://github.com/dennwc))

- More analytics fields for SIPCallInfo. - [#984](https://github.com/livekit/protocol/pull/984) ([@dennwc](https://github.com/dennwc))

### Patch Changes

- Move media related logging utilities from egress to protocol - [#990](https://github.com/livekit/protocol/pull/990) ([@biglittlebigben](https://github.com/biglittlebigben))

- Allow selecting the base logger used by the OverrideLogger - [#991](https://github.com/livekit/protocol/pull/991) ([@biglittlebigben](https://github.com/biglittlebigben))

## 1.34.0

### Minor Changes

- Allow passing all SIP trunk options in CreateSIPParticipant. - [#961](https://github.com/livekit/protocol/pull/961) ([@dennwc](https://github.com/dennwc))

### Patch Changes

- Proto for sending API call details to telemetry. - [#964](https://github.com/livekit/protocol/pull/964) ([@boks1971](https://github.com/boks1971))

## 1.33.0

### Minor Changes

- Add flag to make CreateSIPParticipant synchronous. - [#952](https://github.com/livekit/protocol/pull/952) ([@dennwc](https://github.com/dennwc))

### Patch Changes

- Proto to "report" different kinds of data. - [#962](https://github.com/livekit/protocol/pull/962) ([@boks1971](https://github.com/boks1971))

- Add backup codec policy to AddTrackRequest - [#947](https://github.com/livekit/protocol/pull/947) ([@cnderrauber](https://github.com/cnderrauber))

- Add Ingress OutOfNetwork attribute keys. Add the CanUpdateOwnMetadata claim to the ingress token - [#965](https://github.com/livekit/protocol/pull/965) ([@biglittlebigben](https://github.com/biglittlebigben))

## 1.32.1

### Patch Changes

- Add nonce to SendDataRequest #953 - [#954](https://github.com/livekit/protocol/pull/954) ([@lukasIO](https://github.com/lukasIO))

## 1.32.0

### Minor Changes

- Use iterators in SIP. - [#943](https://github.com/livekit/protocol/pull/943) ([@dennwc](https://github.com/dennwc))

### Patch Changes

- Rename File* related DataStream messages to Byte* - [#948](https://github.com/livekit/protocol/pull/948) ([@lukasIO](https://github.com/lukasIO))

## 1.31.0

### Minor Changes

- Add media encryption options for SIP. - [#892](https://github.com/livekit/protocol/pull/892) ([@dennwc](https://github.com/dennwc))

### Patch Changes

- Add "Enabled" flag to ingresses to allow preventing an ingress to become active without deleting it. - [#937](https://github.com/livekit/protocol/pull/937) ([@biglittlebigben](https://github.com/biglittlebigben))

- Add DataStream.Trailer for finalizing streams - [#940](https://github.com/livekit/protocol/pull/940) ([@lukasIO](https://github.com/lukasIO))

- Add SIPCallDirection to SIPCallInfo - [#938](https://github.com/livekit/protocol/pull/938) ([@biglittlebigben](https://github.com/biglittlebigben))

## 1.30.0

### Minor Changes

- Add filters to SIP list APIs. - [#913](https://github.com/livekit/protocol/pull/913) ([@dennwc](https://github.com/dennwc))

- Add headers for SIP call transfer. - [#926](https://github.com/livekit/protocol/pull/926) ([@dennwc](https://github.com/dennwc))

- Add headers for CreateSipParticipant - [#911](https://github.com/livekit/protocol/pull/911) ([@s-hamdananwar](https://github.com/s-hamdananwar))

- Allow mapping all SIP headers to attributes. - [#920](https://github.com/livekit/protocol/pull/920) ([@dennwc](https://github.com/dennwc))

### Patch Changes

- Allow SIP inbound to specify room configuration - [#923](https://github.com/livekit/protocol/pull/923) ([@davidzhao](https://github.com/davidzhao))

- Add EgressSourceType to EgressInfo - [#894](https://github.com/livekit/protocol/pull/894) ([@biglittlebigben](https://github.com/biglittlebigben))

## 1.29.4

### Patch Changes

- Add version declaration file - [#916](https://github.com/livekit/protocol/pull/916) ([@lukasIO](https://github.com/lukasIO))

## 1.29.3

### Patch Changes

- Fix treehaking possibility of individual imports - [#907](https://github.com/livekit/protocol/pull/907) ([@lukasIO](https://github.com/lukasIO))

## 1.29.2

## 1.29.1

### Patch Changes

- Actually downgrade TypeScript - [#902](https://github.com/livekit/protocol/pull/902) ([@lukasIO](https://github.com/lukasIO))

## 1.29.0

### Minor Changes

- Add DataStream support - [#871](https://github.com/livekit/protocol/pull/871) ([@lukasIO](https://github.com/lukasIO))

### Patch Changes

- Downgrade TypeScript to fix incorrect generated typings - [#901](https://github.com/livekit/protocol/pull/901) ([@lukasIO](https://github.com/lukasIO))

## 1.28.1

### Patch Changes

- fix CJS require importing .js - [#897](https://github.com/livekit/protocol/pull/897) ([@nbsp](https://github.com/nbsp))

## 1.28.0

### Minor Changes

- Add disconnect reason for SIP failures. - [#845](https://github.com/livekit/protocol/pull/845) ([@dennwc](https://github.com/dennwc))

- add native CommonJS support (#883) - [#895](https://github.com/livekit/protocol/pull/895) ([@nbsp](https://github.com/nbsp))

- Map participant attributes to SIP headers. - [#893](https://github.com/livekit/protocol/pull/893) ([@dennwc](https://github.com/dennwc))

- Allow setting number for SIP outbound. - [#891](https://github.com/livekit/protocol/pull/891) ([@dennwc](https://github.com/dennwc))

### Patch Changes

- Report call enabled features in SIPCallInfo - [#884](https://github.com/livekit/protocol/pull/884) ([@biglittlebigben](https://github.com/biglittlebigben))

- Fix port type for SIPUri. - [#882](https://github.com/livekit/protocol/pull/882) ([@dennwc](https://github.com/dennwc))

## 1.27.1

### Patch Changes

- Include room agent dispatch protobufs in JS export - [#875](https://github.com/livekit/protocol/pull/875) ([@davidzhao](https://github.com/davidzhao))

## 1.27.0

### Minor Changes

- Support for room configuration and agent dispatches - [#864](https://github.com/livekit/protocol/pull/864) ([@davidzhao](https://github.com/davidzhao))

### Patch Changes

- Allow requesting a ringtone during SIP call transfers - [#865](https://github.com/livekit/protocol/pull/865) ([@biglittlebigben](https://github.com/biglittlebigben))

## 1.26.0

## 1.25.0

### Minor Changes

- Add SIP analytics events - [#831](https://github.com/livekit/protocol/pull/831) ([@biglittlebigben](https://github.com/biglittlebigben))

- Add ringing timeout and max call duration setting for SIP. - [#844](https://github.com/livekit/protocol/pull/844) ([@dennwc](https://github.com/dennwc))

## 1.24.0

### Minor Changes

- Add disconnect reasons for SIP. - [#828](https://github.com/livekit/protocol/pull/828) ([@dennwc](https://github.com/dennwc))

### Patch Changes

- Expose metrics on javascript package - [#843](https://github.com/livekit/protocol/pull/843) ([@lukasIO](https://github.com/lukasIO))

## 1.23.0

### Minor Changes

- Add RPC types - [#814](https://github.com/livekit/protocol/pull/814) ([@bcherry](https://github.com/bcherry))

- Add TransferParticipant to sip and sip internal services - [#816](https://github.com/livekit/protocol/pull/816) ([@biglittlebigben](https://github.com/biglittlebigben))

### Patch Changes

- Add protocols for client metrics - [#821](https://github.com/livekit/protocol/pull/821) ([@davidliu](https://github.com/davidliu))

- Implement Validate on TransferSIPParticipantRequest - [#818](https://github.com/livekit/protocol/pull/818) ([@biglittlebigben](https://github.com/biglittlebigben))

- Add other_sdks field to ClientInfo - [#804](https://github.com/livekit/protocol/pull/804) ([@bcherry](https://github.com/bcherry))

## 1.22.0

### Minor Changes

- Update SIP protocol. Pass headers, project ID and hostname. - [#805](https://github.com/livekit/protocol/pull/805) ([@dennwc](https://github.com/dennwc))

### Patch Changes

- Add generated flag to ChatMessage - [#813](https://github.com/livekit/protocol/pull/813) ([@lukasIO](https://github.com/lukasIO))

- Add dedicated chat message definition - [#785](https://github.com/livekit/protocol/pull/785) ([@lukasIO](https://github.com/lukasIO))

- Update @bufbuild/protobuf dependency - [#800](https://github.com/livekit/protocol/pull/800) ([@lukasIO](https://github.com/lukasIO))

- Metrics server side timestamp - [#806](https://github.com/livekit/protocol/pull/806) ([@boks1971](https://github.com/boks1971))

## 1.21.0

### Minor Changes

- Add Callee dispatch rule type for SIP. - [#798](https://github.com/livekit/protocol/pull/798) ([@dennwc](https://github.com/dennwc))

### Patch Changes

- Add SDK values for Unity-Web and NodeJS. - [#797](https://github.com/livekit/protocol/pull/797) ([@bcherry](https://github.com/bcherry))

## 1.20.1

### Patch Changes

- Add EnabledCodecs to JoinResponse - [#791](https://github.com/livekit/protocol/pull/791) ([@cnderrauber](https://github.com/cnderrauber))

- Add fast_publish option to JoinResponse - [#796](https://github.com/livekit/protocol/pull/796) ([@cnderrauber](https://github.com/cnderrauber))

## 1.20.0

### Minor Changes

- Send non-error responses also as part of RequestResponse - [#787](https://github.com/livekit/protocol/pull/787) ([@lukasIO](https://github.com/lukasIO))

### Patch Changes

- Add disconnect reason in participant info. - [#788](https://github.com/livekit/protocol/pull/788) ([@boks1971](https://github.com/boks1971))

- Add AgentDispatchInternal service. Add JobTerminate to AgentService - [#782](https://github.com/livekit/protocol/pull/782) ([@biglittlebigben](https://github.com/biglittlebigben))

## 1.19.3

### Patch Changes

- Use glob for generating JS proto definitions - [#779](https://github.com/livekit/protocol/pull/779) ([@lukasIO](https://github.com/lukasIO))

## 1.19.2

### Patch Changes

- Ability to set attributes upon job acceptance - [#769](https://github.com/livekit/protocol/pull/769) ([@davidzhao](https://github.com/davidzhao))

- Add track subscribed first time notification - [#752](https://github.com/livekit/protocol/pull/752) ([@cnderrauber](https://github.com/cnderrauber))

- Rename ErrorResponse Reason INVALID_ARGUMENT to LIMIT_EXCEEDED - [#758](https://github.com/livekit/protocol/pull/758) ([@lukasIO](https://github.com/lukasIO))

- Added RoomClosed as a DisconnectReason - [#778](https://github.com/livekit/protocol/pull/778) ([@davidzhao](https://github.com/davidzhao))

## 1.19.1

### Patch Changes

- Add ErrorResponse - [#743](https://github.com/livekit/protocol/pull/743) ([@lukasIO](https://github.com/lukasIO))

## 1.19.0

### Minor Changes

- Add SIP grants. - [#745](https://github.com/livekit/protocol/pull/745) ([@dennwc](https://github.com/dennwc))

## 1.18.0

### Minor Changes

- Split SIP Trunk configuration to inbound and outbound parts. - [#738](https://github.com/livekit/protocol/pull/738) ([@dennwc](https://github.com/dennwc))

- add Participant attributes key/val storage - [#733](https://github.com/livekit/protocol/pull/733) ([@davidzhao](https://github.com/davidzhao))

## 1.17.0

### Minor Changes

- Add support for additional SIP transports. - [#719](https://github.com/livekit/protocol/pull/719) ([@dennwc](https://github.com/dennwc))

- Add ICERestartWHIPResource to RPC - [#716](https://github.com/livekit/protocol/pull/716) ([@Sean-Der](https://github.com/Sean-Der))

### Patch Changes

- Added error code field to EgressInfo - [#714](https://github.com/livekit/protocol/pull/714) ([@frostbyte73](https://github.com/frostbyte73))

- Include node_id with analytics events - [#727](https://github.com/livekit/protocol/pull/727) ([@davidzhao](https://github.com/davidzhao))

- Add notice to use participant identity from DataPacket for transcriptions. - [#706](https://github.com/livekit/protocol/pull/706) ([@dennwc](https://github.com/dennwc))

## 1.16.0

### Minor Changes

- - Add RedactAutoEncodedOutput to support redacting auto egress types - [#712](https://github.com/livekit/protocol/pull/712) ([@biglittlebigben](https://github.com/biglittlebigben))
  - Redact image outputs
  - Support AliOSS uploads for auto egress

- Allow inbound number filtering on SIP Dispatch Rules - [#707](https://github.com/livekit/protocol/pull/707) ([@dennwc](https://github.com/dennwc))

- Move egress request redacting routines to protocol - [#711](https://github.com/livekit/protocol/pull/711) ([@biglittlebigben](https://github.com/biglittlebigben))

## 1.15.0

### Minor Changes

- Add metadata to SIP trunks, dispatch rules and participants. Change SIP participant identity prefix to `sip_`. - [#696](https://github.com/livekit/protocol/pull/696) ([@dennwc](https://github.com/dennwc))

- Move language into TranscriptionSegment #703 - [#704](https://github.com/livekit/protocol/pull/704) ([@lukasIO](https://github.com/lukasIO))

## 1.14.0

### Minor Changes

- Added real-time Transcription protocol - [#686](https://github.com/livekit/protocol/pull/686) ([@davidzhao](https://github.com/davidzhao))

- WHIP protocol change - [#680](https://github.com/livekit/protocol/pull/680) ([@biglittlebigben](https://github.com/biglittlebigben))

  Deprecate the bypass_transcoding property in all ingress APIs and introduce the optional enable_transcoding property. This property will default to false for WHIP and to true for all other ingress types.

### Patch Changes

- Add SIP participant name. - [#687](https://github.com/livekit/protocol/pull/687) ([@dennwc](https://github.com/dennwc))

## 1.13.0

### Minor Changes

- Add and option to play ringtone for SIP outbound calls. - [#671](https://github.com/livekit/protocol/pull/671) ([@dennwc](https://github.com/dennwc))

## 1.12.0

### Patch Changes

- Fixed bounds check when masking short SIP numbers. - [#650](https://github.com/livekit/protocol/pull/650) ([@dennwc](https://github.com/dennwc))

- Add signal requests for local track updates - [#651](https://github.com/livekit/protocol/pull/651) ([@lukasIO](https://github.com/lukasIO))

- Allow sending DTMF when creating SIP participant. - [#658](https://github.com/livekit/protocol/pull/658) ([@dennwc](https://github.com/dennwc))

## 1.11.0

### Minor Changes

- Align package version with manually tagged golang module - [#646](https://github.com/livekit/protocol/pull/646) ([@lukasIO](https://github.com/lukasIO))

## 1.10.4

### Patch Changes

- Fix granular export paths - [#642](https://github.com/livekit/protocol/pull/642) ([@lukasIO](https://github.com/lukasIO))

## 1.10.3

### Patch Changes

- Export room stubs from package - [#640](https://github.com/livekit/protocol/pull/640) ([@lukasIO](https://github.com/lukasIO))

## 1.10.2

### Patch Changes

- Fix import paths - [#635](https://github.com/livekit/protocol/pull/635) ([@lukasIO](https://github.com/lukasIO))
