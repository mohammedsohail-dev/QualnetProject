# How to run
To run the project, add it to QualNet Software and verify results
  
 # Project Description 
  Network Architecture:
        The project involves multiple subnetworks, each with 5 nodes operating on the same channel.
        Routers act as intermediaries between subnetworks and can listen to two channels.

  Scenario A - TCP and UDP Traffic:
        Objective: Measure values in Application, Transport, and MAC layers.
        Traffic Generation:
            TCP and UDP traffic generated between nodes in different subnetworks.
            Minimum of 500 packets generated.
  Layers Analyzed:
            Application Layer: Analyzed for both TCP and UDP traffic.
            Transport Layer: Examined for protocol-specific characteristics.
            MAC Layer: Assessed for channel utilization and node interactions.

  Scenario B - UDP Connection with Bottleneck Router:
        Objective: Evaluate the impact of a bottleneck router on UDP connections.
        Setup:
            One of the three routers designated as a bottleneck.
            UDP connection characteristics modified for analysis.
        Metrics Analyzed:
            Average Delay in Transmission: Impact of bottleneck on packet transmission time.
            UDP Client Throughput: Throughput from client perspective.
            UDP Server Throughput: Throughput from server perspective.
        Variations:
            Experiment repeated with varying mean packet intervals.
            Comparison made between scenarios with and without 'fading.'

  Conclusion:
        The project aims to understand network behavior under different traffic scenarios and with the introduction of bottleneck routers.
        Findings from both scenarios provide insights into the performance and efficiency of the network architecture.
        The comparison between scenarios with and without 'fading' helps assess the robustness of the system under changing conditions.

  Key Components:
        Multiple subnetworks
        Routers as intermediaries
        TCP and UDP traffic scenarios
        Bottleneck router analysis
        Evaluation of average delay, throughput, and fading effects.

  Outcome:
        The project contributes to a deeper understanding of network performance in a multi-subnetwork environment.
        Findings can inform optimizations and improvements for more efficient communication in complex network architectures.
