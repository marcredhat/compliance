# compliance

https://cloud.ibm.com/docs/openshift?topic=openshift-compliance-operator


https://access.redhat.com/solutions/6047841


https://medium.com/robovision-ai/use-kubernetes-extendedresourcetoleration-to-keep-out-non-gpu-pods-c180f5c5e76d


```
oc get compliancecheckresult
NAME                                                                           STATUS           SEVERITY
roks-cis-node-worker-etcd-unique-ca                                            NOT-APPLICABLE   medium
roks-cis-node-worker-file-groupowner-cni-conf                                  PASS             medium
roks-cis-node-worker-file-groupowner-kubelet-conf                              PASS             medium
roks-cis-node-worker-file-groupowner-multus-conf                               PASS             medium
roks-cis-node-worker-file-groupowner-worker-ca                                 PASS             medium
roks-cis-node-worker-file-owner-cni-conf                                       PASS             medium
roks-cis-node-worker-file-owner-kubelet-conf                                   PASS             medium
roks-cis-node-worker-file-owner-multus-conf                                    PASS             medium
roks-cis-node-worker-file-owner-worker-ca                                      PASS             medium
roks-cis-node-worker-file-permissions-cni-conf                                 PASS             medium
roks-cis-node-worker-file-permissions-kubelet-conf                             PASS             medium
roks-cis-node-worker-file-permissions-multus-conf                              PASS             medium
roks-cis-node-worker-file-permissions-worker-ca                                PASS             medium
roks-cis-node-worker-kubelet-anonymous-auth                                    PASS             medium
roks-cis-node-worker-kubelet-configure-client-ca                               PASS             medium
roks-cis-node-worker-kubelet-configure-event-creation                          FAIL             medium
roks-cis-node-worker-kubelet-configure-tls-cipher-suites                       FAIL             medium
roks-cis-node-worker-kubelet-disable-hostname-override                         PASS             medium
roks-cis-node-worker-kubelet-enable-iptables-util-chains                       PASS             medium
roks-cis-node-worker-kubelet-enable-streaming-connections                      PASS             medium
roks-cis-node-worker-kubelet-eviction-thresholds-set-hard-imagefs-available    FAIL             medium
roks-cis-node-worker-kubelet-eviction-thresholds-set-hard-imagefs-inodesfree   FAIL             medium
roks-cis-node-worker-kubelet-eviction-thresholds-set-hard-memory-available     FAIL             medium
roks-cis-node-worker-kubelet-eviction-thresholds-set-hard-nodefs-available     FAIL             medium
roks-cis-node-worker-kubelet-eviction-thresholds-set-hard-nodefs-inodesfree    FAIL             medium
roks-cis-node-worker-kubelet-eviction-thresholds-set-soft-imagefs-available    FAIL             medium
roks-cis-node-worker-kubelet-eviction-thresholds-set-soft-imagefs-inodesfree   FAIL             medium
roks-cis-node-worker-kubelet-eviction-thresholds-set-soft-memory-available     FAIL             medium
roks-cis-node-worker-kubelet-eviction-thresholds-set-soft-nodefs-available     FAIL             medium
roks-cis-node-worker-kubelet-eviction-thresholds-set-soft-nodefs-inodesfree    FAIL             medium
```
