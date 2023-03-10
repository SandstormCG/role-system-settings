system-settings
=========

Ansible galaxy role for system settings


Role Variables
--------------

* amd_packages --> Array with amd driver packages to install. Example: vars/(arch|neon|tw).yml
* nvidia_packages --> Array with nvidia driver packages to install. Example: vars/(arch|neon|tw).yml
* konsave_config --> Konsave exported file name (without extension)
* gaming_devices --> Array of binding files without extension. Example: `gaming_devices: ["80-custom-kb","90-custom-ms"]`
* cert_file --> Selfsigned .pem file name
* git_email --> Email to set for git global config
* git_name --> username to set for git global config
* ssh_keys --> Array with ssh key files
* btrfs_snaps --> Configure snapper or timeshift (Value can be: "snapper" | "timeshift")
* user --> Username for the installation user
* ansible_ext --> Where to get ansible extra resources
* gpu --> which gpu to install drivers for (none|amd|nvidia)


License
-------

Yet to be determined

Author Information
------------------

[Sandstorm](https://github.com/SandstormCG)
