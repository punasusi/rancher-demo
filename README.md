# rancher-demo


This example will deploy the [Kubernetes sample guestbook](https://github.com/kubernetes/examples/tree/master/guestbook/) application.
The app will be deployed into the `rancher-demo` namespace.

The application will be customized as follows per environment:

* Dev clusters: Only the redis leader is deployed and not the followers.
* Prod clusters: Scale the front deployment to 3.


# source
copied from https://github.com/rancher/fleet-examples
