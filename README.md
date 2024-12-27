# Bandit Level 0 Walkthrough

## Connecting to Bandit Server

To connect to the Bandit server, use the following command:

```bash
ssh bandit0@bandit.labs.overthewire.org -p 2220
```

The password for `bandit0` is:

```
bandit0
```

## Accessing the Password for Level 1

Once you are logged in, use the `cat` command to view the contents of the `readme` file:

```bash
cat readme
```

The password for the next level is mentioned in the `readme` file.

# Bandit Level 1 Walkthrough

## Connecting to Bandit Level 1

To connect to Bandit Level 1, use the following command:

```bash
ssh bandit1@bandit.labs.overthewire.org -p 2220
```

Use the password obtained from Level 0 to log in.

## Accessing the Hidden File

1. List the files in the directory:
   ```bash
   ls
   ```

2. To view the contents of the hidden file named `-`, use the following command:
   ```bash
   cat ./-
   ```

# Bandit Level 2 Walkthrough

## Connecting to Bandit Level 2

To connect to Bandit Level 2, use the following command:

```bash
ssh bandit2@bandit.labs.overthewire.org -p 2220
```

Use the password obtained from Level 1 to log in.

## Accessing the File with Spaces in Its Name

1. List the files in the directory:
   ```bash
   ls
   ```

2. To view the contents of the file named `spaces in this filename`, use the following command:
   ```bash
   cat spaces\ in\ this\ filename
   ```

3. The password for the next level is contained within this file.

# Bandit Level 3 Walkthrough

## Connecting to Bandit Level 3

To connect to Bandit Level 3, use the following command:

```bash
ssh bandit3@bandit.labs.overthewire.org -p 2220
```

Use the password obtained from Level 2 to log in.

## Accessing the Hidden File

1. List all files, including hidden ones, in the directory:
   ```bash
   ls -a
   ```

2. To view the contents of the hidden file named `...Hiden-From-You`, use the following command:
   ```bash
   cat "...Hiden-From-You"
   ```

3. The password for the next level is contained within this file.
