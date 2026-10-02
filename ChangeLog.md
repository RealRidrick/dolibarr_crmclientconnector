# CHANGELOG CRMCLIENTCONNECTOR FOR [DOLIBARR ERP CRM](https://www.dolibarr.org)

## Unreleased

- Fix: email account status values were hardcoded in French (Brouillon/Actif/Désactivé); they now use the core translation keys Draft/Enabled/Disabled, so they follow the user's language
- Fix: left menu titles now use translation keys (CRMClientConnectorMenu, ListOfEmailAccounts, NewEmailAccount)
- Fix: module description pointed to a non-existent key; now uses ModuleCRMClientConnectorDesc
- Add: Dutch translation (langs/nl_NL)
- Add: missing translation keys and permission labels (Permission141911xx) in en_US and fr_FR

## 1.1.0

- Add supplier proposal support (type 'spro') to LINKABLE_ELEMENT_TYPES, NUMBERING_MODULE_TYPES, CATEGORY_TYPES and CATEGORY_TYPE_RIGHTS, so the Thunderbird extension's linked-documents, ref-detection and tags features cover supplier proposals like every other document type

## 

- Add whoami endpoint (GET crmclientconnector/whoami) to identify the current API user without requiring users/info's rights
- Fix compatibility V18 V0.1.1
Initial version V0.1.0
