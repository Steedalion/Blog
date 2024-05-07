While data-based applications for machines are becoming more prevalent, their human counterparts have lagged behind. This is largely due to challenges in measuring and modeling.

# Measuring Challenges

Humans are significantly more difficult to measure than their machine counterparts. Firstly, because machines operate longer hours. We can easily have machine operators for 20 or more hour shifts, whereas doing the same for a human is simply unethical. These longer operating hours mean we can gather more data from machines over longer windows of time.

The second challenge is the effect of measuring. While retrofitting a machine with additional sensors presents no challenges, the same cannot be said for humans. Measuring operator's state, performance, and activities are invasive. While this may seem like a small issue that can be overcome with time, higher levels of stress are associated with a greater risk of injury and lower performance levels[]. This poses the direct problem that measuring adversely affects the performance of operators, not revealing their true performance. In the case of wearable gloves and sensor-based instrumentation and tools, the cause is not psychological but physical. These gloves, tools, etc., directly interfere with the operator's agency, comfort, task familiarity, and ability to perform the given task. In the end, the act of measuring human operators can inhibit their performance, leading to biased data.

The third issue of ethical use of data is of growing concern. In general, there have been numerous scandals involving mega-corporations like Google, Facebook, and Amazon regarding the abuse of general users' data [[Cambridge analytica](10.1016/j.ijhcs.2020.102498)]. While Europe has regulated the storage location and uses of citizen data [[GDPR](https://gdpr-info.eu/)], they have also begun looking at the ethical use of data in the workforce [[1](10.1111/1468-2230.12357)], quoting the right to privacy [[Article 8](https://www.echr.coe.int/documents/d/echr/Guide_Art_8_ENG)]. Regulations inhibit the sharing of data between business entities and limit the application of data for hiring based on performance.

It becomes clear that we cannot blindly apply the techniques used to measure machines to measuring humans. We need to be careful, as the operator's impression is likely to affect the adoption of this technology. Public perception will also affect adoption and application, as we must be careful to remember that systems serve humans [IEEE message], and Asimov's laws of robotics must be adhered to in order not to raise the public's anxiety to stories like Terminator, The Matrix, and iRobot.

# Modelling Challenges

Another, not totally independent issue, is the challenge of modeling human behaviour and performance. Humans are inherently complex to model, and more complex models require more data, recursively indicating the feedback loop of challenges between human data and practical application.

The complexity of human models is caused by a few characteristics best juxtaposed with their machine counterparts. Firstly, humans exhibit dynamic behaviour that can change rapidly over time due to states like learning and fatigue. Machine models, on the other hand, tend to operate under predefined rules and exhibit steady-state behaviour. This becomes obvious when we compare a 12-hour shift of industrial robot assembly with that of manual assembly. Human operators' performance is likely to suffer from reduced throughput and increased errors, while machine performance remains unchanged. Modelling the dynamic behaviour of humans is challenging and often requires real-time data.

Revealing the second issue, that human internal states like learning and fatigue are not directly measurable. This leads to estimation and observation of ill-defined quantities that can only be relatively defined. There is no absolute measure for fatigue and learning, making models relevant only within a small domain (limited transference).

Repeatability in measurements are also an issue influenced by long-term learning, interindividual variability, and biological factors. These issues are suggestive of a probablistic model instead of a deterministic one, again make modelling challenging and may require additional data. 

Human states can interact, leading to complex behaviour. For example, a fatigued operator will learn slower. Similarly, a well-learned operator will accumulate less fatigue from a task.

# Summary

The challenges associated with measuring and modelling human operators compound each other. While the cost associated with acquiring data is high due to sensors inhibiting operator performance, the amount of data acquired is significantly lower due to to the limited workhours of human operators. To compound this human models are significantly more complex due to their dynamic, probabilistic, interacting, and indirectly measurable state. These complex models require more data. The models are also only valid within a small domain, limiting the resuse of data.

Applying the technologies developed for machines to humans is insufficient to meet the challenges. The data acquisition, data usage, and models need to be closely examined to ensure they meet the ethical requirement of "serving humans." For example, invasive and inhibiting sensors, data used for performance and disciplinary action, and unempathetic operator models are just a few of the issues that arise when applying existing machine-based approaches to human operators. It is my view that acknowledging the complexity of the task at hand will yield more creative solutions.  
