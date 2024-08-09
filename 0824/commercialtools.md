# Commercial Solutions For Github Backup 

*Update: 22/07/24*

Companies offering commercial (paid) solutions for backing up Github repositories. 

Note: companies tend to update their pricing and terms regularly. This information will likely become quickly outdated. For latest information, check with the vendors listed.

## Git Protect 

Site: [GitProtect.io](https://www.gitprotect.io)

### Pricing

Pricing is on a per-repository basis. At the time of this update, it's €63/70 repos. 

This might be an affordable proposition for companies and startups, but may be beyond the budget of private users with lots of repositories to backup.

### Supported Clouds

Listed [here](https://helpcenter.gitprotect.io/deployment-and-the-storage-overview/storage-backup-destination/cloud-storage). But basically: S3-compliant object storage or use their storage. 

Expressly supported:

- GitProtect Cloud (storage provided by GitProtect Company)
- AWS
- Wasabi
- Azure Blob Storage
- BackBlaze B2
- Google Cloud Storage

---

## Rewind Backups

Rewind is the surprise winner in the "cheap and cheerful" category although they don't allow you to bring-your-own-cloud (BYOC).

For your typical active (private) Github user with a lot of repos to backup but whose doesn't want to commit to paying hundreds of dollars per month just for Github backup, this (IMO) makes the most sense.

The big drawback, however: no BYOC support on this tier. 

Site: [Rewind Backups](https://rewind.com/products/backups/github/)

### Pricing

Currently $14/user/month for **unlimited repos**

### Supported Clouds

On this tier, it's just backup onto proprietary storage.

---

## Cloudback.it

Site: [link](https://cloudback.it/pricing)

Currently, their pricing is:

**Basic plan:**

$10/month (for 10 repos)
$75/month (for 100 repos)
$500/month (for 1,000 repos)

Their list of integrations is [here](https://cloudback.it/integrations) and includes OpenStackSwift and Alibaba Cloud (as well as GCP, AWS, etc).

---

## Backup Labs

Site: [link](https://backuplabs.io/integrations/github-backup/)

Pricing here is (again) on a per-repository basis.

The individual plan for up to 100 repos (or gists) is currently $50/month (which falls to $40/month on annual billing).

For each backup there's 30 day retention.

Their website says that they're "powered by" AWS but they don't allow users to BYOC on the backup plans.