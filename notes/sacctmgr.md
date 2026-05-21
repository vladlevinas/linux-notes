# sacctmgr

> Source: TLDR (MIT) — from 'vendor/tldr/'

# sacctmgr

> View, setup, and manage Slurm accounts.
> More information: <https://slurm.schedmd.com/sacctmgr.html>.

- Show current configuration:

`sacctmgr show configuration`

- Add a cluster to the slurm database:

`sacctmgr add cluster {{cluster_name}}`

- Add an account to the slurm database:

`sacctmgr add account {{account_name}} cluster={{cluster_of_account}}`

- Show details of user/association/cluster/account using a specific format:

`sacctmgr show {{user|association|cluster|account}} format="Account%10" format="GrpTRES%30"`

---
_Imported: 2026-05-21 20:52:05 UTC_
