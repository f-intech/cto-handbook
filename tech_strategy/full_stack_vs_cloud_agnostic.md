# "Full stack cloud" or cloud agnostic approach to application building?

A "full stack cloud" approach is one that takes full advantage of a global cloud provider like AWS or Azure. Bespoke services are taken advantage of, even if that means lockin to the cloud provider.

## Full Stack Cloud Benefits
1. By using a broad range of services from a cloud provider (as opposed to multiple tech vendors), you reduce the vendor due diligence required, and the overall vendor management.
2. Integrated solutions between multiple offerings from the same cloud provider are often easier to setup, especially when it comes to IAM.

## Cloud Agnostic Benefits
1. As a SaaS vendor, your customer's may dictate how you can deploy. If they want a deployment to their cloud provider (or even on-premises), will you support it? This is a commercial decision before a tech decision.

## Additional Considerations
1. Even in the case of a "full stack cloud approach", organisations should prepare sensible cloud exit plans. Even if the exit will take 12 months, it should have been roughly conceptualised.
2. Many approaches that avoid vendor lock-in simply create lock-in to another tech stack. One can avoid vendor lock-in to ECS by using Kubernetes, but now you have lock-in to Kubernetes. Just because a technology is non-proprietary does not mean you don't have lockin.
