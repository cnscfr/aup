# README - CNSC Acceptable User Policy

*source: https://supercomputing.ec-nantes.fr/charter*

I agree with all terms and conditions listed below and I consent to having this website store my submitted information so they can respond to my inquiry. Data here will be used only for the user creation account by the ICI-CNSC. Any question or request, please contact our dpo@ec-nantes.fr .

ICI-CNSC’s HPC services are provided on shared resources. To ensure equitable access for all HPC projects, certain restrictions on acceptable use are necessary. All use of HPC services must adhere to the following guidelines. Accounts repeatedly violating these guidelines will have their HPC access disabled.

1. Access to the HPC Linux cluster (**Liger**) is to be via SSH to respective login nodes or to the XCS Web Portal by https and all access to compute nodes must be via SLURM. Direct access to compute nodes is not permitted.

  1. A maximum number of concurrent login sessions will be enforced on login nodes.
  2. SSH sessions that have been idle for an amount of time will be automatically disconnected.
  3. These limits will be adjusted as necessary to manage login node resources and to comply with applicable security standards.

2. The purpose of a login node is to provide access to the cluster via SSH and to prepare for running a program (e.g., editing files, compiling, and submitting batch jobs). Processes that use a non-trivial amount of compute or memory resources must not be run on any of the shared login nodes. These processes may be run via SLURM. Processes running on login nodes that have used significant CPU time or that are using significant memory resources will be terminated without notice.

3. Scratch file system (/scratch) are intended to be used as data storage for running jobs or files under active analysis. Use of techniques for purpose of protecting files from the automated purge of scratch file systems is not permitted. Files on these file systems may be deleted at any time and are not backed up – the only copy of important files should not be kept on these file systems.

4. To extent feasible, jobs run on HPC resources are expected to make efficient use of the resources.

5. Resources requested for jobs should be as accurate as possible even if such requests result in longer queue waiting times (e.g. if jobs require majority of per node memory they should use exclusive option even though this will likely increase the time the job will wait in queue).

6. Compute nodes which have lost contact with SLURM for more than a few hours or which are unreachable from the console will be rebooted without notice.

Listed charters MUST BE READ, AGREED AND SIGNED BY THE APPLICANT (please send us back ONLY the page with your signatures and thank you again for considering the environment for not printing all the pages)

1. ICI-CNSC Acceptable Use Policy For HPC Resources (Download & Sign)
2. RENATER Acceptable Use Policy – Réseau National de télécommunications pour la Technologie l’Enseignement et la Recherche (french version). (Download & Sign)
3. ANSSI (Agence Nationale de la Sécurité des Systèmes d’Information) recommendations for the use of passwords.
4. ECN IT Acceptable Use Policy (french version) (Download & Sign)
