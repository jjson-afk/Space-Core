Galaxy Network is a networking solution primarily designed for use in game engines such as Unity, Unigine, and Stride (Xenko). However, it can be used in any environment supporting C# .NET Standard 2.0+.
The solution consists of a client and server component, both provided as a set of libraries plugged into the project. Galaxy Network can operate in both authoritative and relay modes. The currently supported functionality is listed below.

Installation instructions : https://youtu.be/eo6nW2DM0TE

Network: Authorization/registration. Network connection tracking. Automatic NAT support. Automatic connection recovery. Traffic encryption support. Packet spoofing protection. Support for messages with and without guaranteed delivery, with sorting and queuing. Support for automatic drop of obsolete messages. Routing (server, client, instance, entity).

Instances (rooms, worlds, locations): Creation. Getting a list. Instance manager. Login/Logout. Broadcasting a message to all instance clients. Client management support. Automatic and manual host transfer for non-authoritarian or partially authoritarian logic. Full support for authoritarian logic. Physics support. Network frame support (1 to 120 network fps). Ability to set a login password. Ability to create invisible instances.

Physics: support for primitive colliders. Terrain collider support. Tools for baking scene colliders for the server. Ray cast with tag and dynamic object support. Support for linear and angular acceleration.

Network entities (network objects): Creation/deletion. Server-side physics support. Client-side control support. Ability to transfer an object to another player or switch to an authoritarian model. Ability to balance objects between clients. Support for authoritarian server control. Ability to directly exchange messages between entity instances. Entity creation and deletion functionality (+ go). Built-in functionality for synchronizing position and orientation in space.

Other features: Built-in Protobuf support. Built-in Bit serializer.

Supported backends: Mono support. il2cpp support. Net Standard 2.0 compliant. ECS, Jobs, and Dots support. Can be used outside of Unity. Stride (Xenko) support. Experimental Unigine engine support.

Supported server platforms: Windows, Linux, MacOS.

Supported and tested platforms (for the client): Windows, Linux, MaxOS, Android, iOS. In theory, other platforms should also be supported, except WebGL.

In alpha: Synchronization of animator parameters.

General:

The solution is distributed as an open-source template and a set of closed-source libraries. There is no direct dependency on the database type; any supported .NET framework can be used.

Installation Instructions https://youtu.be/sDxyENBw77E

Galaxy Network is a network solution designed primarily for use in game engines such as Unity, Unigine, Stride (Xenko). However, it is possible to use in any other environment supporting c # net Standart 2.0+. The solution consists of client and server parts, both are presented as a set of libraries connected to the project. Galaxy network is able to work both in authoritarian mode and in repeater mode. Below is a set of currently supported features.

Net: Authorization / registration. Accounting for network connections. Automatic work with NAT. Auto reconnect. Support traffic encryption. Protection against packet spoofing. Support for messages with and without delivery guarantee, with sorting, with priority. Support for automatic drop outdated messages. Routing (server, client, instance, entity).

Instances (rooms, worlds, locations): Creature. Getting the list. Instance manager. Enter exit. Sending a message to all instance clients. Support customer management. Automatic and manual host transfer for non-authoritarian or partially authoritarian logic. Full support for authoritarian logic. Physics support. Support for network frames from (1 to 120 network FPS). Ability to set a password for entry. Ability to create invisible instances.

Physics: support for primitive colliders. terrane collider support. tools for baking scene colliders for the server. ray cast with support for tags and dynamic objects. support for linear and angular acceleration.

Network entities (network objects): Create / delete. Support for server physics. Customer Management Support. The ability to transfer the object to another player, or transfer to an authoritarian model. The ability to balance objects between customers. Support for Authoritarian server management. The ability to directly exchange messages between instances of the entity. Functionality for creating and deleting an entity (+ go). Built-in functionality for synchronizing position and orientation in space.

Other functionality: Native protobuf support. Built-in Bit serializer.

Supported backend: Mono support. Support for il2cpp. Complies with net standart 2.0 specification. Support ECS, Jobs, Dots. Use outside Unity is possible. Support for Stride (Xenko). Experimental support for the Unigine engine.

Platforms supported by the server: Windows Linux MacOS

Supported and tested platforms (for the client): Windows Linux MaxOS. Android iOS In theory, other platforms other than WebGL should be supported.

In alpha: Sync animator settings.

General:

The solution is distributed in the form of an open source template, and a set of private libraries. There is no direct dependence on the type of database, you can use any supported .net
