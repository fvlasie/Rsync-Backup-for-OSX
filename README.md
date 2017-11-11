# Rsync-Backup-for-OSX

An rsync backup script which has been modified to work with OS X Lion. This was written for a file server running Lion (the latest OS supported by the hardware) because Spotlight simply refused to cooperate.

Edit /etc/crontab to contain:
daily root /usr/local/sbin/rsync_backup source/ dest/
