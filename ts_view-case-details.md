---

copyright:

  years: 2020, 2026

lastupdated: "2026-05-19"

keywords: IBM Cloud case, view cases, account access, support center help, resolve issues on the support center, trouble support center, personalized help

subcollection: support

content-type: troubleshoot

---

{{site.data.keyword.attribute-definition-list}}

# Troubleshooting case visibility in IBM Cloud account
{: #ts_viewcasedetails}
{: troubleshoot}

Learn why you can't view all cases in your IBM Cloud account and how to resolve the issue by adjusting user visibility and IAM policies.
{: shortdesc}

When you try to view the support cases that are associated with the account, you can't see all open cases. You can view only users that you invited to the account and users who are in your classic infrastructure user hierarchy.
{: tsSymptoms}

You can't view cases because you don't have the required access to view all cases in the account. You might not be able to view all cases because the account owner is restricting user list visibility in your account. For more information, see [Controlling user visibility](/docs/iam?topic=iam-iam-user-setting#userlistview).

When the user list is restricted in your account, you must have two policies to view all cases. First, and IAM policy with at least the Viewer role on the User management account management service, and second, a policy on the Support Center account management service. To view your current access, in the {{site.data.keyword.cloud_notm}} console, go to **Manage** > **Access (IAM)**, and select your name from the **Users** page. Click the **Access policies** tab.
{: tsCauses}

Another reason that you can't view a case is that the case was created as an {{site.data.keyword.IBM}} support case, which requires different access.

If the case was created as an {{site.data.keyword.cloud_notm}} case, you can contact the account owner to request the appropriate IAM policies. If the issue was created as an {{site.data.keyword.IBM}} support case, contact the account owner and request Full Access. For more information about {{site.data.keyword.IBM}} support cases, see [Working with the User Administration Page](https://www.ibm.com/mysupport/s/article/Administrator-Management?language=en_US){: external}
{: tsResolve}
