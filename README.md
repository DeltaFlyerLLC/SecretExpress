# Secret Express

Secret Express V1

**Secret Express: Simple, Scalable, and Reliable Cluster Node Health Management**

Secret Express is a straightforward and effective Python-Flask application, crafted with a focus on managing the health of nodes in clusters. It is especially tailored for Cosmos SDK and CometBFT nodes, combining simplicity with a proven track record of reliability, making it a practical choice for both monitoring and maintaining cluster health.

Key Features:

1. **Cluster-Specific Health Management**: Secret Express is designed to perform thorough health checks on each node, providing an accurate and complete view of your cluster's health, with an emphasis on simplicity and clarity.

2. **User-Friendly Python and Flask Design**: Developed in Python and using the Flask framework, the application offers an accessible and modifiable codebase, making it straightforward for ehancement.

3. **Battle-Tested and Scalable**: Secret Express is proven in demanding production environments, handling clusters with billions of queries. This experience underlines its capacity to perform consistently in various scales, from small clusters to those exceeding 70 nodes.

4. **Automated Node Management for Easy Maintenance**: The application efficiently identifies and removes unhealthy nodes based on configurable parameters, simplifying the upkeep of your cluster.

5. **Integrated Load Balancer Management**: After removing unhealthy nodes, Secret Express seamlessly manages updating which nodes are included in the cluster without interruption, ensuring smooth and continuous load balancing.

6. **Flexible for a Range of Applications**: Beyond its primary blockchain focus, Secret Express serves as a reliable framework for various commercial and non-commercial use cases that require robust cluster management and custom health checks.

7. **Public Reporting for Accountability and Transparency**: It includes public reporting features, allowing third parties or private entities to view historical performance data. This function is crucial for environments where transparency and third-party insights are essential.

Secret Express stands out as a simple yet robust solution for node health management in clusters. Its battle-tested nature in high-load environments and adaptable framework make it a dependable and versatile tool in a wide range of operational scenarios.

**Expanded Future Development and Enhancements for Secret Express**

Secret Express, in its journey to enhance cluster node health management, is considering a range of improvements and new features. These developments aim to augment the application's efficiency, adaptability, and overall functionality.

1. **Transition to Web Socket-Based Health Checks**: Currently, Secret Express allows configurable frequency for health checks. A future enhancement being contemplated is the implementation of health checks using Web sockets. This would enable real-time, continuous monitoring of node health. However, considering that block times are generally above six seconds each, the immediate incentive to switch to Web sockets might not be compelling. The transition would nonetheless offer improved responsiveness and precision in health monitoring over the long term.

2. **Auto Repair Functionality Integration**: The application is looking to integrate an auto repair feature to automatically resolve issues in individual nodes using predefined solutions. This would minimize manual intervention, enhancing the clusters efficiency and reliability.

3. **Advanced Caching Strategies**: Incorporating advanced caching mechanisms is also on the horizon. This feature aims to reduce the load on clusters, focusing on effective management and portability of cached data from archive nodes, thereby improving performance and scalability.

4. **Support for a Wider Range of Load Balancers**: Plans include extending support to other widely-used load balancers like Nginx. This expansion would make Secret Express more versatile, allowing for easy integration with various load balancing tools, accommodating diverse cluster environments.

5. **Enhancement of Health Checks**: There are plans to enhance the range of health checks conducted by Secret Express. Potential additions include checks for the chain ID and the specific node software version in use, to ensure consistency across the cluster. These checks would be relatively straightforward to implement and could significantly improve the monitoring precision. Another improvement could be enforcing node config consistency such for app and config files on nodes. Additionally, based on different use cases and needs, many other specialized health checks could be integrated, further customizing the tool to suit diverse operational requirements.

**Note**: Some of these features, while tested in isolation, are not yet integrated into Secret Express. They represent a possible direction for future updates. These enhancements, if implemented, will further solidify Secret Express as a comprehensive and forward-thinking solution in its domain.


Development Background of Secret Express

Secret Express was developed by @PrivatePixels and supported by Delta Flyer LLC, independently and without external funding of any kind. Its journey to version 1 included multiple refactors and rewrites, ensuring its effectiveness in cluster node health management. The testing phase, crucial for its reliability, was conducted through the API team’s Load Balancer, highlighting a commitment to thorough, real-world application and refinement.

Permissive license choice for “Secret Express” 

https://www.gnu.org/licenses/agpl-3.0.en.html

**Note: Any deployment of this software over a network that includes modifications must explicitly be open sourced and made publicly available under this same license, in accordance with the AGPL's requirements. This applies when the modified software is distributed or used to provide network services."**

The Affero General Public License (AGPL) is an open-source license that has a strong focus on network use of licensed software. Here's a summary of its key aspects:

1. **Network Use as Distribution**: The main feature that distinguishes AGPL from other licenses like the GPL is that it considers the use of software over a network as equivalent to distribution. This means if you run AGPL-licensed software on a server and others interact with it remotely, you must provide the source code under the AGPL.

2. **Copyleft License**: The AGPL is a strong copyleft license. This means that any derivative work based on the AGPL-licensed software must also be released under the AGPL, ensuring that all modifications and derived works remain free and open.

3. **Source Code Availability**: When distributing or providing network access to software licensed under the AGPL, you are required to make the source code available to users. This ensures that users can access, modify, and share the software's source code under the same license terms.

4. **Modification and Redistribution**: Users can modify and redistribute the software, provided they also license these modifications under the AGPL.

5. **Compatibility with Other Licenses**: The AGPL is not always compatible with other open-source licenses, which can limit its integration with software under different licenses.

6. **Suitability for SaaS**: The AGPL is particularly suitable for software delivered as a service (SaaS), as it closes the so-called "Application Service Provider (ASP) loophole" present in the GPL. This loophole allowed SaaS providers to use GPL-licensed software without sharing changes, as they weren't technically 'distributing' the software.

7. **Versioning**: The current version, AGPLv3, is often seen alongside GPL licenses, as it was designed to close gaps related to network use in those licenses.

The AGPL is ideal for developers who want to ensure their software remains free and open in a networked environment, especially in cases where the software is used to provide a service over the internet.
