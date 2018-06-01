# WinSSHFS
========================

Fork of Masaeedu's CLI only Fork of Martin Dimov's WinSSHFS project. Removes the GUI, exposes clean library interface, adds a CLI.

CLI usage is:

```
SSHFS 1.0.0.0
Copyright c  2017

  -d, --drive-letter    Required. Drive letter to mount the remote SFTP path 
                        under

  -r, --path            Required. Absolute path of directory to be mounted from
                        remote system

  -h, --host            Required. IP or hostname of remote host

  -p, --port            (Default: 22) SSH service port on remote server

  -u, --username        Required. Name of SSH user on remote system

  -x, --password        Read password from stdin

  -k, --private-keys    Path to SSH user's private key(s), if key-based auth 
                        should be attempted

  --help                Display this help screen.

  --version             Display version information.

```
### Getting this Fork
Starting work on this fork. See plans below. If you would like a working build now you can visit Masaeedu's Fork release page [here](https://github.com/masaeedu/win-sshfs/releases/latest)
~~Builds can be found on the [releases page](https://github.com/sparkx120/win-sshfs/releases/latest)~~

### Plans

- [ ] Add background option to run a new sshfs connection as a service or background command in powershell
- [ ] Add support for auto reconnect without disabling the drive when network changes
- [ ] Stability and Performance improvements
- [ ] Eventual support of the Dockan 2.0.x library (when it is no longer beta)
