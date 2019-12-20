---
benefit: The organisation leverages common security solutions.
costs: Difficult to say, but let's give it a try.
dependencies:
- 41069df2385749b190f46e8a776e6339
- 41069df2385749b190f46e8a776e6339
- 41069df2385749b190f46e8a776e6339
id: 9b6a86278ba14a9098d3d60a9a78d6c5
level: 41c8e63716c34f1eaf09b8cad70cfbaf
metrics:
- metric1
- metric2
notes: 'My first thought goes here.

  My second thought goes here.'
personnel:
- Architect
- Developer
- Tester
results:
- result1
- result2
shortDescription: Establish common design patterns and security solutions
stream: 253b012094cf4e0988e08fd22609227d
title: Evaluate common services and design patterns to establish baseline security
  postures and processes for adoption.

---
Identify shared infrastructure or services with security functionality. These typically include single-sign-on services, access control or entitlements services, logging and monitoring services or application-level firewalling. Collect and evaluat reusable systems to assemble a list of such resources and categorize them by the security mechanism they fulfill. Consider each resource in terms of why a development or an operations team would want to integrate with it, i.e. the benefits of using the shared resource.
If multiple resources exist in each category, select and standardize on one or more shared service per category. Because future software development will rely on these services, review each thoroughly to ensure understanding of the baseline security posture. For each selected service, create design guidance for development teams to understand how to integrate with the system. Make the guidance available to development or operations teams through training, mentorship, guidelines, and standards.
Establish a set of general design patterns representing sound methods of implementing security functionality. You can research them or purchase them, and it is often even more effective if you customize them so they are more specific to your organization. Example patterns include a single-sign-on subsystem, a cross-tier delegation model, a separation-of-duties authorization model, a centralized logging pattern, etc.
These patterns can originate from specific projects or applications, but make sure you share them between different development and/or operations teams across the organisation for efficient and consistent application of appropriate security solutions.
To increase adoption of these patterns, link them to the shared security services, or implement them into actual component solutions that can be easily integrated into an application during development. Support the key technologies within the organisation, for instance in case of different development stacks (LINK TO Technology Management). Treat these solutions as actual applications with proper support in case of questions or issues.