# aws-p2p-ml-svcs

A peer-2-peer platform that provides users with machine learning services such as image generation and text generation.

## Architecture
![](assets/diagram.png)

## Setup

NOTE: This is an initial testing setup

First run relay-server. Get the peer id of that from the logs.

Update config.json in ml-txt-gen-node with above peerid. Next run txt-gen-node.

Update config.json in user-node with above peerid. Next run user-node, this sends a Hello World message to txt-gen-node.