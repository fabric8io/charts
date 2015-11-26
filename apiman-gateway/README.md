##Apiman Gateway

The Apiman Gateway is part of API Management. The Apiman Gateway requires the 
Elasticsearch service to be up and running. The Fabric8 gateway uses the Apiman engine to enforce policies and plans that are published to the gateway using the Apiman management console. Note that the Apiman management app runs in a different container.

For more details please see the <a href="http://fabric8.io/guide/apimanComponents.html">User Guide on API Management </a> and the <a href="http://www.apiman.io/">Apiman website</a>.

By default this gateway is setup in the apiman management console during the bootstrap process. You can check in this console under admin > gateways > ApimanGateway using the 'Test Config' that connectivity to the gateway is configured correctly (see also http://fabric8.io/guide/apimanGettingStarted.html).
