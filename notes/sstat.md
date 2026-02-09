# sstat

> Source: TLDR (MIT) — from 'vendor/tldr/'

# sstat

> View information about running jobs.
> More information: <https://slurm.schedmd.com/sstat.html>.

- Display status information of a comma-separated list of jobs:

`sstat {{[-j|--jobs]}} {{job_id}}`

- Display job ID, average CPU and average virtual memory size of a comma-separated list of jobs, with pipes as column delimiters:

`sstat {{[-p|--parsable]}} {{[-j|--jobs]}} {{job_id}} {{[-o|--format]}} {{JobID,AveCPU,AveVMSize}}`

- Display list of fields available:

`sstat {{[-e|--helpformat]}}`

---
_Imported: 2026-02-09 14:15:58 UTC_
