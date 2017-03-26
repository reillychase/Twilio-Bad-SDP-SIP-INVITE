# Twilio-Bad-SDP-SIP-INVITE
Solution for Twilio "Bad SDP" response

Cisco SPA params to fix:

    <RTP_Packet_Size ua="na">0.020</RTP_Packet_Size>
    <Insert_VIA_rport group="SIP/NAT_Support_Parameters">Yes</Insert_VIA_rport>
