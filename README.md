# HCOSS oEmbed Format

A Drupal module that adds the oEmbed provider name to the filename of the
entity.

The idea is to automatically add the provider name to the filename of the 
oembed file my using hook_entity_presave and hook_entity_insert to add the
provider name whenever the entity is saved. The provider is also hidden on
the entity edit form using hook_form_alter.