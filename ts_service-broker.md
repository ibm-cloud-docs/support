---

copyright:

  years: 2015, 2026
lastupdated: "2026-05-19"

keywords: IBM Cloud support case, create support case, edit support case, IAM policies, support center, help support center, resolve issues support center, help getting support

subcollection: support

content-type: troubleshoot

---

{{site.data.keyword.attribute-definition-list}}

# Troubleshooting IBM Cloud support case creation and editing issues
{: #ts-edit-case}
{: troubleshoot}

Resolve issues with creating or editing IBM Cloud support cases due to access restrictions and learn how to assign necessary IAM policies.
{: shortdesc}

When you try to create a case, the following error message is displayed:
{: tsSymptoms}

```text
Looks like you don't have access to create cases for this account.
```

General problems with accessing and managing support cases might be caused by
not having the Identity and Access Management (IAM) access policy for the Support Center account management service. You must be assigned the editor or administrator role on the support center account management service to create cases.
{: tsCauses}

The account owner, an administrator on the support center service, or the administrator on all account management services can assign an IAM policy on the support center to manage cases.
{: tsResolve}

If you're the account owner or an administrator of the Support Center, complete the following steps to create an access policy for working with support cases:

1. In the {{site.data.keyword.cloud_notm}} console, go to **Manage** > **Access (IAM)** and select **Users**.
1. Select a username, and click **Access policies**.
1. Click **Assign Access**.
1. From the Assign users additional access section, select **Account management**.
1. For the type of access that you want to assign, select **Support Center**.
1. Select a role to define the level of access for the user. The user needs the Editor or Administrator role to view, search, create, and update support cases.
