# checkrcmount

Runs the command `rclone listremotes` for each configured remote in rclone, then checks if each mount is authorized and accessible. 

Outputs a list of 'failed' mounts that need to be re-authorized and writes that list to a file called `failedmounts` .
