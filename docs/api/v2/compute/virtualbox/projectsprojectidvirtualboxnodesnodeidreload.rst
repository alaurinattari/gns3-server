/v2/compute/projects/{project_id}/virtualbox/nodes/{node_id}/reload
------------------------------------------------------------------------------------------------------------------------------------------

.. contents::

POST /v2/compute/projects/**{project_id}**/virtualbox/nodes/**{node_id}**/reload
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
Reload a VirtualBox VM instance

Parameters
**********
- **project_id**: Project UUID
- **node_id**: Node UUID

Response status codes
**********************
- **204**: Instance reloaded
- **400**: Invalid request
- **404**: Instance doesn't exist

Sample session
***************


.. literalinclude:: ../../../examples/compute_post_projectsprojectidvirtualboxnodesnodeidreload.txt

