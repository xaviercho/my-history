# my-history
Description:
As noted, individual commits on GitHub are associated with timestamps that indicate their commit times. Nevertheless, it's possible to manipulate these timestamps, allowing us to alter the appearance of commits to appear as though they were made at times other than their actual commit moments. Further through the series we can also add fake contributors and add verified organizations to the list.

Solution Description:
- Adding commits recursively and then randomly modifying the dates.
- To counter the risk of forged contributor identities, GitHub introduced "Commit Signature Verification." This allows users to cryptographically sign their commits, ensuring their authenticity. However, this feature verifies the signatures themselves, not their presence. Enabling "vigilant mode" enhances the feature by displaying verification status for all commits, highlighting unsigned ones and helping detect impersonation attempts.

Output:
- See visual commits 

Tests:
[x] added to a proxy account

For educational purposes only, Reference:
https://checkmarx.com/blog/unverified-commits-are-you-unknowingly-trusting-attackers-code/?utm_keyword=&utm_campaign=NA-AD-20230530-ALL_LEVEL-GOOGLE-DES-PER-SEARCH-DSA&utm_source=adwords&utm_medium=ppc&utm_term=&hsa_acc=2852355864&hsa_cam=20219818529&hsa_grp=150559350198&hsa_ad=660401585194&hsa_src=g&hsa_tgt=dsa-2085949482612&hsa_kw=&hsa_mt=&hsa_net=adwords&hsa_ver=3&gclid=CjwKCAjwrranBhAEEiwAzbhNtRurjhI8DMRf6Yn6V3XNqH8ZkJ-W_kLqplJGw_qM-1WAYHnHKrItXxoCF3kQAvD_BwE

