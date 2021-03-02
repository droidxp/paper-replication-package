## Replication Package

This is the replication package for the paper *Mining Android Sandboxes Using Dynamic and Static Analysis: a
Non-exact Replication Study*. 

### Authors

   * Francisco Handrick da Costa
   * Ismael Medeiros
   * Thales Menezes
   * João Victor da Silva
   * Ingrid Lorraine da Silva
   * Rodrigo Bonifácio
   * Krishna Narasimhanb
  
### Abstract

The use of sandboxes is an effective technique for malware analysis. However, although the use of dynamic
analysis for mining Android sandboxes has been investigated before, little is known about the potential
benefits of combining static and dynamic analysis for mining Android sandboxes. Accordingly, in this paper
we present the results of two studies that investigate whether or not static analysis might complement and
increase the performance of dynamic analysis tools for mining Android sandboxes. In the first study we
conduct a non-exact replication of the Bao et al. study, a previous work that compares the performance
of test case generation tools for mining Android sandboxes. Differently from the original work, here we
isolate the effect of the static analysis tool (DroidFax) they used to instrument the Android apps in their
experiments. This decision was motivated by the fact that DroidFax could have influenced the efficacy of
the dynamic analyses positively—through the execution of specific static analysis algorithms. In our second
study, we carried out a new experiment to investigate the efficacy of tainted analysis algorithms for mining
Android sandboxes. To this end, we executed the FlowDroid tool to mine the source-sink flows from the
benign/malign pairs of Android apps used in the Bao et al. study. Our study brings several findings. For
instance, the first study reveals that DroidFax alone (static analysis) can detect 43.75% of the malwares in
the dataset of the Bao et al. work, leading to an overestimation of the performance of the dynamic analysis
tools. The results of the second study show that (static) taint analysis is also practical for mining Android
sandboxes, with a performance similar to that reached by dynamic analysis tools.

## Link to the replication package

   * [HTML File](https://htmlpreview.github.io/?https://github.com/droidxp/paper-replication-package/blob/master/replication.html)