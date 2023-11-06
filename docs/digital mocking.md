# Digital mocking 

Mocking involves using a model to test or develop a system component under specific conditions (state). Typically a mock component is substituted for a production component through a standardized interface. This has the effect of testing the system response under a specific state.

An interface hides the substitution making the mock indistinguishable from the actual component. 

![mocking-db-example](C:\Users\steed\Nextcloud6\Blog\blog\docs\images\mocking-db-example.png)
The database (DB) example illustrates how different states of a DB are tested without modifying the production DB. This allows testing and development of an empty, full, or locked DB without disrupting production.

## Digital mocking

Digital mocking is this pattern specialized to the digital twin. The interface is now used to obscure the replacement of the physical component with its digital twin.



While this approach is common in the domain of industrial robots, where high-fedlity physics simulation environments are employed. Hence, we first applied this pattern to the digital twin concept for development and testing purposes of an industrial robotic assembly cell [Industrial robot]. The facilitated the creative insight that eye-in-hand cameras and fixed cameras could be used for reconfigurable feeding.

## Human-centric digital mocking

While substituting a human operator with a computational human performance model is feasible for large scale simulation, it ignores the wicked nature of socio-technical systems[]. Therefore HIL simulations may still be necessary. 

We further specialize it to facilitate human-centric designs using virtual reality.
