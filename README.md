# s3fs_ubuntu_integration

## Installation

* Debian 9 and Ubuntu 16.04 or newer:

  ```
  sudo apt install s3fs
  ```
Enter your credentials in a file `${HOME}/.passwd-s3fs` and set
owner-only permissions:

```
echo ACCESS_KEY_ID:SECRET_ACCESS_KEY > ${HOME}/.passwd-s3fs
chmod 600 ${HOME}/.passwd-s3fs
```
## Scripting

'touch addmounter.sh'
Copy and Pate contents

## Cron Jobs

32 3 * * *   sudo sh /xxxx/addmounter.sh



