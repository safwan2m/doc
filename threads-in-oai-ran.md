## Threads in OAI RAN. 

**ru_thread**: ru_thread includes the reading and writing of data to and from the radio devices, it makes use of threadpool for split 8 if low phy processing needs to be included in the RAN, if not no thread-pool required. This particular thread can be pinned to a CPU core through ru_thread_core configuration.  </br></br>
**L1_tx_thread**: L1_tx_thread includes the high phy L1 processing and calling the scheduler. The L1_tx_thread can be pinned to a core using the L1_tx_thread_core parameter under L1 configurations. </br></br>
**L1_rx_thread**: L1_tx_thread includes the high phy L1 processing and sends indications to the scheduler about the received data for Uplink MAC processing. The L1_rx_thread can be pinned to a core using the L1_rx_thread_core parameter under L1 configurations. </br></br>
**L1_stats**: </br></br>
**MAC_STATS**: </br></br>
**RLC queue**: </br></br>
**pdcp data ind**: </br></br>
**pdcp_timer**: </br></br>
**TASK_RRC_GNB**: </br></br>
**TASK_GNB_APP**: </br></br>
**TASK_GTPV1_U**: </br></br>
**TASK_SCTP**: </br></br>
**TASK_NGAP**: </br></br>
