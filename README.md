# ansible-playbooks-lizardfs
Initial working draft,

The aim is to provide automate deployment of default cluster system across chosen number of storage nodes,
Scripts has to be edited to supply valid IPs, ansible hosts, goals etc.

Installation:

	lizardfs_install_centos.yml
	lizardfs_install_debian.yml
	
Initial configuration:

 	lizardfs_initial_config.yml 	
 
Reminder, for xfs mount chunks with:

	sudo mount -o rw,noexec,nodev,noatime,nodiratime,largeio,inode64,barrier=0 /dev/<array> /mnt/disks/chunk<n>
