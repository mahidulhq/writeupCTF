# Git Commits Challenge Walkthrough

The challenge mentions **"commits,"** which indicates it involves **Git**. Let’s start by downloading the challenge files.

```bash
wget https://artifacts.picoctf.net/c_titan/159/challenge.zip
unzip challenge.zip
````

Next, navigate to the extracted folder and list the files:

```bash
cd [extracted-folder]
ls
```

You should see a Python file. Although you can view its content using:

```bash
cat file-name.py
```

it’s not necessary for this challenge.

To explore the Git commit history, use:

```bash
git log
```

or to see commits related to the Python file specifically:

```bash
git log file-name.py
```

This will display a list of commits similar to the screenshot below:

![Image description](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/fc05gxhxtfoxx5gx7zpo.png)

The commits are listed from the oldest to the newest.
The flag `picoCTF{_______}` is hidden somewhere in these commit messages.

For example, I found the flag here:

![Image description](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/e9p3hcb5zoifivr5xhjn.png)

