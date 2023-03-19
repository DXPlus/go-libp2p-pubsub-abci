# go-libp2p-pubsub-abci

This repository is forked from go-libp2p-pubsub, and some logic has been modified to support only gossip topic.

We only modified the gossipsub.go file.

## Install

```
go get github.com/DXPlus/go-libp2p-pubsub-abci
```

## Usage

If you want to use the only-gossip topic, please change your topic name like this: 

```
flag := "GossipOnlyTopic"
topicName := topic + flag // "topic" is the original name of your topic 
```

## License

The go-libp2p-pubsub-abci project is dual-licensed under Apache 2.0 and MIT terms:

- Apache License, Version 2.0, ([LICENSE-APACHE](./LICENSE-APACHE) or http://www.apache.org/licenses/LICENSE-2.0)
- MIT license ([LICENSE-MIT](./LICENSE-MIT) or http://opensource.org/licenses/MIT)
