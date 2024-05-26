# Hierarchical vs Heterarchical networks

Two distinct network structures exist.  In Hierarchical networks, elements are connected in specific network structures with supervisors coordinating communication between subordinates. This leads to supervisory elements possessing different levels of control. Hierarchical networks on the other hand are flat/horizontal, where all elements contain the same level of authority/control.

## Hierarchical networks

Hierarchical networks are prevalent in SCADA systems. In such systems, multiple machines may report to a single supervisory controller, and these controllers, in turn, report to a central control room. However, two significant limitations arise:

1. **Limited Flexibility**: Control and monitoring cannot be flexibly aggregated across the network. Devices under different supervisors or levels cannot easily communicate due to the lack of direct network paths.
2. **Scalability Challenges**: Expanding the system's scale is not straightforward. Introducing a new supervisor to the network necessitates complex configurations and adjustments.

![hierarchical](HierarchyVsHeterachy\hierarchical.bmp)

## Heterarchical networks 

Heterarchical networks, commonly found in IoT environments, operate on a flat structure, enabling entities to communicate freely, unlike hierarchical networks where communication is constrained by levels. This flat structure leads to a dynamic network topology, manifesting in several ways:

1. **Enhanced Flexibility**: Communication and control are highly flexible as all entities are interconnected.
2. **Scalability and Adaptability**: Scaling up is facilitated by adding additional supervisors, typically representing intelligent services. These supervisors can manage tasks such as scheduling across multiple machines and machine maintenance. Moreover, scaling in terms of field devices or physical entities is simple, utilizing existing supervisors and allowing for future changes.
3. **Security Considerations**: However, security becomes a concern as all entities have access to one another, potentially complicating data flow management and access control.

  

![heter](HierarchyVsHeterachy\heter.bmp)

## Dynamic network topology

Heterarchical networks facilitate dynamic network topology, allowing for the reconfiguration of the network structure over time. In software,  this entails reconfiguring the network topology to connect the necessary entities. This adaptability enables the network to evolve as needed,  connecting only essential entities initially and expanding to include  more later.



![heter](HierarchyVsHeterachy\dyn_networks.bmp)

The Publisher-Subscriber model, also known as Pub-Sub model, is a  messaging pattern used in distributed systems for communication between  various components or services. In this model, there are three main  entities: publishers, subscribers, and a message broker or middleware. The publisher-subscriber model is a good example of a dynamic network implementation. Due to the loose coupling subscibers

![heter](HierarchyVsHeterachy\pubsub.bmp)

