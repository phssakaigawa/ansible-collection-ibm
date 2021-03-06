
ibm_pi_instance -- Configure IBM Cloud 'ibm_pi_instance' resource
=================================================================

.. contents::
   :local:
   :depth: 1


Synopsis
--------

Create, update or destroy an IBM Cloud 'ibm_pi_instance' resource



Requirements
------------
The below requirements are needed on the host that executes this module.

- IBM-Cloud terraform-provider-ibm v1.8.1
- Terraform v0.12.20



Parameters
----------

  pi_progress (False, float, None)
    Progress of the operation


  min_processors (False, float, None)
    Minimum number of the CPUs


  pin_policy (False, str, None)
    PIN Policy of the Instance


  pi_memory (True, float, None)
    (Required for new resource) Memory size


  pi_volume_ids (False, list, None)
    List of PI volumes


  health_status (False, str, None)
    PI Instance health status


  pi_processors (True, float, None)
    (Required for new resource) Processors count


  pi_cloud_instance_id (True, str, None)
    (Required for new resource) This is the Power Instance id that is assigned to the account


  pi_replication_policy (False, str, none)
    Replication policy for the PI INstance


  pi_pin_policy (False, str, none)
    Pin Policy of the instance


  min_memory (False, float, None)
    Minimum memory


  instance_id (False, str, None)
    Instance ID


  pi_sys_type (True, str, None)
    (Required for new resource) PI Instance system type


  max_processors (False, float, None)
    Maximum number of processors


  pi_replicants (False, float, 1)
    PI Instance repicas count


  pi_network_ids (True, list, None)
    (Required for new resource) Set of Networks that have been configured for the account


  status (False, str, None)
    PI instance status


  migratable (False, bool, None)
    set to true to enable migration of the PI instance


  max_memory (False, float, None)
    Maximum memory size


  pi_proc_type (True, str, None)
    (Required for new resource) Instance processor type


  pi_replication_scheme (False, str, suffix)
    Replication scheme


  pi_user_data (False, str, None)
    Base64 encoded data to be passed in for invoking a cloud init script


  pi_instance_name (True, str, None)
    (Required for new resource) PI Instance name


  reboot_for_resource_change (False, str, None)
    Flag to be passed for CPU/Memory changes that require a reboot to take effect


  addresses (False, list, None)
    None


  pi_image_id (True, str, None)
    (Required for new resource) PI instance image name


  pi_key_pair_name (True, str, None)
    (Required for new resource) SSH key name


  id (False, str, None)
    (Required when updating or destroying existing resource) IBM Cloud Resource ID.


  state (False, any, available)
    State of resource


  zone (False, str, None)
    Denotes which IBM Cloud zone to connect to in multizone environment. This can also be provided via the environment variable 'IC_ZONE'.


  region (False, str, us-south)
    The IBM Cloud region where you want to create your resources. If this value is not specified, us-south is used by default. This can also be provided via the environment variable 'IC_REGION'.


  ibmcloud_api_key (True, any, None)
    The IBM Cloud API key to authenticate with the IBM Cloud platform. This can also be provided via the environment variable 'IC_API_KEY'.













Authors
~~~~~~~

- Jay Carman (@jaywcarman)

