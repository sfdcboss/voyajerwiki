---
layout: default
title: Account
parent: duplicateRules
grand_parent: Metadata
---
# Metadata Type
duplicateRules


# Filename 
Account


# Raw XML
```
<?xml version="1.0" encoding="UTF-8"?>
<DuplicateRule xmlns="http://soap.sforce.com/2006/04/metadata" xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance">
    <actionOnInsert>Allow</actionOnInsert>
    <actionOnUpdate>Allow</actionOnUpdate>
    <alertText>You are creating a duplicate record. We recommend you use an existing record instead.</alertText>
    <description>Duplicate Rule for Accounts using the Standard Account Matching Rule</description>
    <duplicateRuleFilter xsi:nil="true"/>
    <duplicateRuleMatchRules>
        <matchRuleSObjectType>Account</matchRuleSObjectType>
        <matchingRule>Account_Matching_Rule</matchingRule>
        <objectMapping xsi:nil="true"/>
    </duplicateRuleMatchRules>
    <isActive>false</isActive>
    <masterLabel>Standard Account Duplicate Rule</masterLabel>
    <operationsOnInsert>Alert</operationsOnInsert>
    <operationsOnInsert>Report</operationsOnInsert>
    <operationsOnUpdate>Report</operationsOnUpdate>
    <securityOption>EnforceSharingRules</securityOption>
    <sortOrder>1</sortOrder>
</DuplicateRule>
```


# Last Modified


# Usage
