My name is Mark Chmarny and I currently focus on helping developers write modern apps in any language or framework with http://dapr.io. 

Few things from my recent work: 
 * [Hardening Dapr apps](https://github.com/mchmarny/dapr-demos/tree/master/hardened) example of multi-microservice app with tightly controlled access to secrets, components, and full invoking service identity validation
 * [Scaling Kubernetes deployment](https://github.com/mchmarny/dapr-demos/tree/master/autoscaling-on-queue#autoscaling-dapr-service-based-on-queue-depth) that processes queue messages based on the back-pressure of that queue (aka topic lag) 
 * [Processing pipeline](https://github.com/mchmarny/dapr-demos/tree/fanout-eventhubs/pipeline) combining Twitter and cognitive APIs with pub/subs and WebSocket app to monitor topic sentiment
 * [Fan-out pattern](https://github.com/mchmarny/dapr-demos/tree/master/fan-out#fan-out-demo) for "broadcasted" single message to multiple configurable types of targets (e.g. Redis PubSub, HTTP, gRPC)
 * [Continuous deployment using GitHub actions](https://github.com/mchmarny/git-ops) simple pipeline for test, image, and deploy app onto Kubernetes cluster
  
I usually share my longer thoughts at https://m.chmarny.com and the shorter ones on https://twitter.com/mchmarny

![My github stats](https://github-readme-stats.vercel.app/api?username=mchmarny&show_icons=true)
