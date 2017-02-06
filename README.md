# kube-build
CI Server API extension for Kubernetes

# What is this?
If you are not using Kubernetes or don't care what the hell is that, then probably you want to stop here and explore other repositories on Github.

# Motivation:
There are various free and hosted build servers are already there. They are all amazing but I want something that I can have full control over it, not complex, plays nicely with Kubernetes and easy to extend and maintain. 

There is nothing out there that can actually provides you all these features at once. My goal to build one!

# How it works:
Imagine you can deploy your build instructions just like your normal pods into your cluster and then every commit will trigger a build and you can control and see the build process inside your Kubernetes cluster. After the build is done you can update your cluster deployments and the build container gets destroyed.

# Sounds interesting?
I'm at a very early stages of this project, any help is appreciated. Just fork it at make a pull request.


