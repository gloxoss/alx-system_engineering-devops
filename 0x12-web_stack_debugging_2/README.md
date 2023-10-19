# Project 0x12: Web Stack Debugging #2

**Project Description:**

This project is part of the ALX School curriculum and is designed to help you develop your web stack debugging skills. You will work on two mandatory tasks and have the opportunity to unlock advanced tasks to further enhance your understanding of web stack debugging.

## Mandatory Tasks

### 0. Run Software as Another User

**Task Description:**

The user 'root' is a superuser in the Linux environment and can perform any action, which can be both advantageous and risky. In this task, you will create a Bash script that allows you to run the `whoami` command as another user passed as an argument.

**Requirements:**

- Write a Bash script that accepts one argument.
- The script should run the `whoami` command under the user passed as an argument.
- Test your script with different users.

**Example:**

```bash
root@ubuntu:~# whoami
root
root@ubuntu:~# ./0-iamsomeoneelse www-data
www-data
root@ubuntu:~# whoami
root
```

**File:** `0-iamsomeoneelse`

### 1. Run Nginx as Nginx

**Task Description:**

In this task, you will ensure that the Nginx web server is running as the less privileged 'nginx' user rather than the 'root' user. This enhances security by limiting the impact of any potential security breaches.

**Requirements:**

- Configure Nginx to run as the 'nginx' user.
- Make sure Nginx is listening on all active IPs on port 8080.
- You cannot use `apt-get remove`.
- Write a Bash script that configures the container as specified.

**After Debugging:**

You should see Nginx running as the 'nginx' user when checking the process list and Nginx listening on port 8080.

**File:** `1-run_nginx_as_nginx`

## Advanced Tasks (Unlockable)

Advanced tasks may be available for this project. Please refer to the ALX Africa Intranet for details on how to unlock and complete these tasks.

## Project Submission

Ensure that your project meets the following requirements:

- All your files are interpreted on Ubuntu 20.04 LTS.
- All your files end with a newline.
- A `README.md` file is included at the root of the project folder.
- All your Bash script files are executable.
- Your Bash scripts pass Shellcheck without any errors.
- Your Bash scripts run without errors.
- The first line of all your Bash scripts is `#!/usr/bin/env bash`, followed by a comment explaining what each script does.

## About ALX

ALX is a highly regarded institution for learning software engineering and DevOps. This project is a part of the curriculum designed to enhance your skills and knowledge in these fields. For any questions or clarifications, please reach out to your instructors or refer to ALX's guidelines.

---

**Copyright © 2023 ALX, All rights reserved.**

**Project Author:** Sylvain Kalache, co-founder at Holberton School