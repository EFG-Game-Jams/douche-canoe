# Design

## Concepts

- [What is WebRTC](https://medium.com/av-transcode/what-is-webrtc-and-how-to-setup-stun-turn-server-for-webrtc-communication-63314728b9d0)
  - [TURN server](https://webrtc.org/getting-started/turn-server)
- [Unity NetCode](https://docs-multiplayer.unity3d.com/)
- [NetworkTransport interface](https://github.com/Unity-Technologies/com.unity.netcode.gameobjects/blob/develop/com.unity.netcode.gameobjects/Runtime/Transports/NetworkTransport.cs)

## The Plan

1. Create a chat client in Unity using WebRTC

   - Requires a TURN server
   - Proof of concept, does not guarrantee `com.unity.multiplayer` will play nicely

2. Create a simple 3D multiplayer "walk around in a shared room" demo
   - Determines if WebRTC and `com.unity.multiplayer` can be friends
