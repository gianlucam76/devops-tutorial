Webinar recording can be found [here](https://www.youtube.com/watch?v=Y3dW5XYjg5I&feature=youtu.be)

Sveltos's **Pull Mode** is a crucial feature designed to enable Sveltos to manage Kubernetes clusters in scenarios where the traditional "push" model (where the management cluster directly communicates with the managed clusters' API servers) is not feasible or desired. This is particularly relevant for:

- **Firewalled or Air-Gapped Environments**: Clusters that are isolated from the management cluster by firewalls, NATs, or even air gaps, preventing direct inbound connections.
- **Private Cloud or Edge Deployments**: Where network connectivity might be limited or restricted.
- **Security and Compliance**: When security policies dictate that managed clusters should not expose their API servers directly to the management network.
