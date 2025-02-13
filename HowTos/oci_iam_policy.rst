.. meta::
  :description: Describe how to customize OCI IAM role
  :keywords: account, aviatrix, OCI IAM policy, OCI, compartment


==================================
OCI IAM least privilege policy
==================================

When the Aviatrix Controller uses Oracle Cloud Infrastructure APIs to manage networking, gateway, and firewall resources; the following IAM Policies can be implemented for least privilege.
In OCI, IAM is managed through groups and policies. The policy boundary can span a single compartment or an entire tenancy.

If you wish to limit the Controller access permissions, you can do so by creating a group with a set of policies used 
by the Controller as shown below and scope policy to the compartment. This document describes what the minimal set of policies are.  `Oracle Cloud IAM documentation <https://docs.oracle.com/en-us/iaas/data-safe/doc/iam-policies.html>`_
covers IAM concepts and technical implementation detail.

1. Aviatrix minimal required OCI IAM Policy bound by Compartment
----------------------------------------------------------------


    Allow group <YOUR GROUP NAME> to manage volume-family in compartment <YOUR COMPARTMENT>

    Allow group <YOUR GROUP NAME> to manage instance-family in compartment <YOUR COMPARTMENT>

    Allow group <YOUR GROUP NAME> to manage virtual-network-family in compartment <YOUR COMPARTMENT>

    Allow group <YOUR GROUP NAME> to inspect all-resources in compartment <YOUR COMPARTMENT>

    Allow group <YOUR GROUP NAME> to inspect app-catalog-listing in compartment <YOUR COMPARTMENT>

    Allow group <YOUR GROUP NAME> to read app-catalog-listing in compartment <YOUR COMPARTMENT>

    Allow group <YOUR GROUP NAME> to manage app-catalog-listing in compartment  <YOUR COMPARTMENT>
 
   
 
2. Assign the OCI user to the group
-----------------------------------


3. Onboard the OCI user 
--------------------------------

Follow the OCI account onboarding instructions here for the OCI user `here <https://docs.aviatrix.com/HowTos/oracle-aviatrix-cloud-controller-onboard.html>`_

.. note::

  If you are deploying Transit FireNet that requires OCI Marketplace agreement. For example, Palo Alto 
  VM-Series firewalls. You will need to login as the user created and accept the agreeement from the vendor
  in the compartment and region and version for the firewall deployment. See the screenshots below for reference.

|pan_fw_subscribe|

|pan_fw_accepted_agreement|

.. |pan_fw_subscribe| image:: oci_iam_policy_media/pan_fw_subscribe.png
   :scale: 30%

.. |pan_fw_accepted_agreement| image:: oci_iam_policy_media/pan_fw_accepted_agreement.png
   :scale: 30%

.. disqus::
