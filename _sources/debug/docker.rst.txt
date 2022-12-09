docker
======================



Tips
--------------

.. code-block:: shell
   :caption: stop all containers

   docker stop $(docker ps -aq)

.. code-block:: shell
   :caption: rm all containers

   docker rm $(docker ps -aq)

.. code-block:: shell
   :caption: delete all images

   docker rmi $(docker images -aq)

.. code-block:: shell
   :caption: delete all

   docker system prune -a -f