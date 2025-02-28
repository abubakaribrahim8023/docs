---
title: Downgrading your GitHub subscription
intro: 'You can downgrade the subscription for any type of account on {% data variables.location.product_location %} at any time.'
redirect_from:
  - /github/setting-up-and-managing-billing-and-payments-on-github/downgrading-your-github-subscription
  - /articles/downgrading-your-personal-account-s-billing-plan
  - /articles/how-do-i-cancel-my-account
  - /articles/downgrading-a-user-account-to-free
  - /articles/removing-paid-seats-from-your-organization
  - /articles/downgrading-your-organization-s-paid-seats
  - /articles/downgrading-your-organization-s-billing-plan
  - /articles/downgrading-an-organization-with-per-seat-pricing-to-free
  - /articles/downgrading-an-organization-with-per-repository-pricing-to-free
  - /articles/downgrading-your-organization-to-free
  - /articles/downgrading-your-organization-from-the-business-plan-to-the-team-plan
  - /articles/downgrading-your-organization-from-github-business-cloud-to-the-team-plan
  - /articles/downgrading-your-github-billing-plan
  - /articles/downgrading-your-github-subscription
  - /github/setting-up-and-managing-billing-and-payments-on-github/managing-billing-for-your-github-account/downgrading-your-github-subscription
versions:
  fpt: '*'
  ghec: '*'
topics:
  - Accounts
  - Downgrades
  - Organizations
  - Repositories
  - User account
shortTitle: Downgrade subscription
---
## Downgrading your {% data variables.product.product_name %} subscription

When you downgrade your personal account or organization's subscription, pricing and account feature changes take effect on your next billing date. Changes to your paid personal account or organization subscription does not affect subscriptions or payments for other paid {% data variables.product.prodname_dotcom %} features. For more information, see "[AUTOTITLE](/billing/managing-billing-for-your-github-account/how-does-upgrading-or-downgrading-affect-the-billing-process)."

## Downgrading your personal account's subscription

If you downgrade your personal account from {% data variables.product.prodname_pro %} to {% data variables.product.prodname_free_user %}, the account will lose access to advanced code review tools on private repositories. {% data reusables.gated-features.more-info %}

{% data reusables.user-settings.access_settings %}
{% data reusables.user-settings.billing_plans %}
1. Under "Current plan", use the **Edit** drop-down and click **Downgrade to Free**.
  ![Screenshot of the "Current plan" section of the billing settings page. The "Edit" dropdown menu is expanded and highlighted with an orange outline.](/assets/images/help/billing/downgrade-to-free.png)
5. Read the information about the features your personal account will no longer have access to on your next billing date, then click **I understand. Continue with downgrade**.

If you published a {% data variables.product.prodname_pages %} site in a private repository and added a custom domain, remove or update your DNS records before downgrading from {% data variables.product.prodname_pro %} to {% data variables.product.prodname_free_user %}, to avoid the risk of a domain takeover. For more information, see "[AUTOTITLE](/pages/configuring-a-custom-domain-for-your-github-pages-site/managing-a-custom-domain-for-your-github-pages-site)."

## Downgrading your organization's subscription

{% data reusables.dotcom_billing.org-billing-perms %}

If you downgrade your organization from {% data variables.product.prodname_team %} to {% data variables.product.prodname_free_team %} for an organization, the account will lose access to advanced collaboration and management tools for teams.

If you downgrade your organization from {% data variables.product.prodname_ghe_cloud %} to {% data variables.product.prodname_team %} or {% data variables.product.prodname_free_team %}, the account will lose access to advanced security, compliance, and deployment controls. {% data reusables.gated-features.more-info %}



{% note %}

**Notes:**
  - If your organization is owned by an enterprise account, billing cannot be managed at the organization level. To downgrade, you must remove the organization from the enterprise account first. For more information, see "[AUTOTITLE](/enterprise-cloud@latest/admin/user-management/managing-organizations-in-your-enterprise/removing-organizations-from-your-enterprise)."
  - If you're currently trialing {% data variables.product.prodname_ghe_cloud %}, and you don't purchase {% data variables.product.prodname_enterprise %} before the trial ends, your organization will be automatically downgraded to {% data variables.product.prodname_free_team %} or {% data variables.product.prodname_team %}. For more information, see "[AUTOTITLE](/get-started/signing-up-for-github/setting-up-a-trial-of-github-enterprise-cloud#finishing-your-trial)."

{% endnote %}

{% data reusables.organizations.billing-settings %}
1. Under "Current plan", use the **Edit** drop-down and click the downgrade option you want.
  ![Screenshot of the "Current plan" section of the billing settings page. The "Edit" dropdown menu is expanded and highlighted with an orange outline.](/assets/images/help/billing/downgrade-to-free.png)
{% data reusables.dotcom_billing.confirm_cancel_org_plan %}

## Downgrading an organization's subscription with legacy per-repository pricing

{% data reusables.dotcom_billing.org-billing-perms %}

{% data reusables.dotcom_billing.switch-legacy-billing %} For more information, see "[AUTOTITLE](/billing/managing-billing-for-your-github-account/upgrading-your-github-subscription#switching-your-organization-from-per-repository-to-per-user-pricing)."

{% data reusables.organizations.billing-settings %}
5. Under "Subscriptions", next to your current subscription, select the **Edit** dropdown menu and click **Edit plan**.
1. Under "Billing/Plans", next to the plan you want to change, click **Downgrade**.
1. Enter the reason you're downgrading your account, then click **Downgrade plan**.

## Removing paid seats from your organization

To reduce the number of paid seats your organization uses, you can remove members from your organization or convert members to outside collaborators and give them access to only public repositories. For more information, see:
- "[AUTOTITLE](/organizations/managing-membership-in-your-organization/removing-a-member-from-your-organization)"
- "[AUTOTITLE](/organizations/managing-user-access-to-your-organizations-repositories/converting-an-organization-member-to-an-outside-collaborator)"
- "[AUTOTITLE](/organizations/managing-user-access-to-your-organizations-repositories/managing-an-individuals-access-to-an-organization-repository)"

{% data reusables.organizations.billing-settings %}
1. Under "Current plan", next to your current plan, select the **Edit** dropdown menu, then click **Remove seats**.
1. Under "Remove seats", select the number of seats you'd like to downgrade to.
1. Review the information about your new payment on your next billing date, then click **Remove seats**.

## Further reading

- "[AUTOTITLE](/get-started/learning-about-github/githubs-products)"
- "[AUTOTITLE](/billing/managing-billing-for-your-github-account/how-does-upgrading-or-downgrading-affect-the-billing-process)"
- "[AUTOTITLE](/billing/managing-your-github-billing-settings/about-billing-on-github)."
- "[AUTOTITLE](/billing/managing-billing-for-your-github-account/about-per-user-pricing)"
