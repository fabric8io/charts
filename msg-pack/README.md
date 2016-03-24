The msg-pack Package provides the MsgGateway and Artemis deployments. Although Artemis can be deployed as 
a single instance, its recommended that communication is done wth the MsgGateway. This is a proxy, that handles
distribution of messages across multiple Artemis brokers and allows for scaling Artemis brokers.
