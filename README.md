# SignalingAPI

The [Signaling API](https://docs.derivative.ca/Palette:signalingServer#Signaling_API) is describing the message types being exchanged between a [signaling server](https://docs.derivative.ca/Palette:signalingServer) and its clients or between client and client when they are routing message through the signaling server.

If a 3rd party application wishes to connect with [TouchDesigner](https://derivative.ca)'s own signaling server, the messages being exchanged should comply with the Signaling API described in the following section.

Note that some components can be developed to subscribe to signaling messages through the [signalingClient COMP](https://docs.derivative.ca/Palette:signalingClient) Subscribe() method.

i.e. The [WebRTC COMP](https://docs.derivative.ca/Palette:webRTC) is subscribing to messages being exchanged through the signaling server and clients, and complying with the Signaling API.
