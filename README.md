## Replication Package

This is the replication package for the paper *Exploring the Use of Static and Dynamic Analysis to Improve the Performance of the Mining Sandbox Approach for Android Malware Identification*. 

### Authors

   * Francisco Handrick da Costa
   * Ismael Medeiros
   * Thales Menezes
   * João Victor da Silva
   * Ingrid Lorraine da Silva
   * Rodrigo Bonifácio
   * Krishna Narasimhanb
   * Márcio Ribeiro
  
### Abstract

The popularization of the Android platform and the growing number of Android applications (apps) that manage sensitive data turned the Android ecosystem into an attractive target for malicious software. For this reason, researchers and practitioners have investigated new approaches to address Android's security issues, including techniques that leverage dynamic analysis to mine Android sandboxes. The mining sandbox approach consists in running dynamic analysis tools on a benign version of an Android app. This exploratory phase records all calls to sensitive APIs. Later, we can use this information to (a) prevent calls to other sensitive APIs (those not recorded in the exploratory phase) or (b) run the dynamic analysis tools again in a different version of the app. During this second execution of the fuzzing tools, a warning of possible malicious behavior is raised whenever the new version of the app calls a sensitive API not recorded in the exploratory phase.

The use of a mining sandbox approach is an effective technique for Android malware analysis, as previous research works revealed. Particularly, existing reports present an accuracy of almost 70% in the identification of malicious behavior using dynamic analysis tools to mine android sandboxes. However, although the use of dynamic analysis for mining Android sandboxes has been investigated before, little is known about the potential benefits of combining static
analysis with a mining sandbox approach for identifying malicious behavior.
Accordingly, in this paper we present the results of two studies that investigate the impact of using static analysis to complement the performance of existing dynamic analysis tools tailored for mining Android sandboxes, in the task of identifying malicious behavior.

In the first study we conduct a non-exact replication of a previous study (hereafter BLL-Study) that compares the performance of test case generation tools for mining Android sandboxes. Differently from the original work, here we isolate the effect of an independent  static analysis component (DroidFax) they used to instrument the Android apps in their experiments. This decision was motivated by the fact that DroidFax could have influenced the efficacy of the dynamic analyses tools positively---through the execution of specific static analysis algorithms DroidFax also implements. In our second study, we carried out a new experiment to investigate the efficacy of taint analysis algorithms to complement the mining sandbox approach previously used to identify malicious behavior. To this end, we executed the FlowDroid tool to mine the source-sink flows from benign/malign pairs of Android apps used in a previous research work.

Our study brings several findings. For instance, the first study reveals that DroidFax alone (static analysis) can detect 43.75% of the malwares in the BLL-Study dataset, contributing substantially in the the performance of the dynamic analysis tools in the BLL-Study. The results of the second study show that taint analysis is also practical to complement the mining sandboxes approach, with a performance similar to that reached by dynamic analysis tools.

## Link to the replication package

   * [HTML File](https://htmlpreview.github.io/?https://github.com/droidxp/paper-replication-package/blob/master/replication.html)
