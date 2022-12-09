k8s
====================

Official links
--------------

kubectl cheatsheet + api reference
https://kubernetes.io/docs/reference/kubectl/


Tips
--------------

.. code-block:: shell
   :caption: count not running deployments,statefulsets

   kubectl -n <k8s_namespace> get deployments,statefulsets | grep 0/ | wc -l

.. code-block:: shell
   :caption: count not running pods

   kubectl -n <k8s_namespace> get pods --no-headers | grep -v Running | grep -v Completed | wc -l

