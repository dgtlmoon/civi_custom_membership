Tricky CiviCRM membership price settings
 - Depending on the date offer different price sets for the membership
 - Always ensure their membership expires on June 30th of the next year

INSTALLATION:

  Enable the module in admin/build/modules
  Apply the MembershipBlock-withPriceSet.tpl.patch
  Clear out your smarty template cache
  Configure the module by editing _membershippriceset_config() and telling it what Membership Id's, PriceSet Id's to tweak
