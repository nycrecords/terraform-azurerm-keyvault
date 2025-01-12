# v4.3.1 - 2021-04-26

Changed
  * AZ-160: Fix default logs retention

# v4.3.0 - 2021-04-21

Breaking
  * AZ-482: `soft_delete_enabled` is now deprecated since provider [v2.42.0](https://github.com/terraform-providers/terraform-provider-azurerm/blob/master/CHANGELOG-v2.md#2420-january-08-2021) and should be removed from this module.
  * AZ-160: Unify diagnostics settings on all Claranet modules

# v4.2.0 - 2021-03-09

Changed
  * AZ-458: Normalizing the casing of the permissions to comply with provider changes https://github.com/terraform-providers/terraform-provider-azurerm/pull/10593

# v4.1.0 - 2021-01-15

Changed
  * AZ-398: Force lowercase on default generated name

# v3.0.1/v4.0.0 - 2020-11-02

Added
  * AZ-248: Force `soft_delete_enabled` value to `true`, add a parameter for `purge_protection_enabled`

Changed
  * AZ-273: Update README and CI, module compatible Terraform 0.13+ (now requires Terraform 0.12.26 minimum version)

# v2.2.0/v3.0.0 - 2020-07-13

Breaking
  * AZ-206: Update README, module compatible both AzureRM provider < 2.0 and >= 2.0 + update variables types

# v2.1.1 - 2020-04-02

Changed
  * AZ-197: Fix README
  * AZ-209: Include Gitlab CI template

# v2.1.0 - 2019-12-20

Added
  * AZ-132: Option to customize Keyvault Network ACLs

# v2.0.1 - 2019-10-07

Changed
  * AZ-119: Revamp README and publish this module to Terraform registry
  * AZ-94: Fix `for_each` with null values thanks to Terraform 0.12.9

Added
  * AZ-119: Add CONTRIBUTING.md doc and `terraform-wrapper` usage with the module

# v2.0.0 - 2019-09-06

Breaking
  * AZ-94: Terraform 0.12 / HCL2 format

Added
  * AZ-118: Add LICENSE, NOTICE & Github badges

# v1.1.0 - 2019-06-18

Changed
  * AZ-98: Make KeyVault tenant id input optional

# v1.0.0 - 2019-05-02

Added
  * AZ-71: First version
