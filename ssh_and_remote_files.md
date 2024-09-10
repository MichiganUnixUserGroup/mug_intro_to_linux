# SSH and Remote Files

SSH (Secure Shell) is a network protocol that allows secure communication between two devices over an untrusted network. It’s mainly used to remotely access and manage servers, network devices, and other systems. SSH protects the communication by encrypting the data, preventing unauthorized access.

Common uses of SSH include:

	•	Logging into remote servers securely.
	•	Running commands on a remote system.
	•	Securely transferring files (via SCP or SFTP).
	•	Tunneling network traffic.

SSH supports two types of authentication: password-based and key-based. Key-based authentication is more secure, using a pair of cryptographic keys (a public key on the server and a private key on the client). SSH usually runs on port 22.

To connect to a remote system with SSH, you use a command like:

```
ssh username@hostname
```


Once connected via SSH, you can perform various tasks on the remote system as if you were physically present. You can navigate directories, manage files, install software, or monitor system processes. 

Some common SSH features include:

	•	Remote command execution: You can run commands on the remote system without logging in interactively, like this:

```
ssh username@hostname "command"
```

	•	File transfer: SSH supports secure file transfers using tools like SCP (Secure Copy) and SFTP (Secure File Transfer Protocol). For example, to copy a file from your local machine to a remote server using SCP:

```
scp localfile username@hostname:/path/to/destination
```

Or 

```
sftp username@remote_host
```

```
lcd /path/to/local_directory
```

```
lpwd
```

```
put local_file.txt /remote/directory/
```

```
get /remote/directory/file.txt /local/directory/
```

```
bye
```



