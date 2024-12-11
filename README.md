# PGMate Demo

## Run it in GitPod

Just click this button to run PGMate demo in the Cloud with GitPod.io:

[![Open in Gitpod](https://gitpod.io/button/open-in-gitpod.svg)](https://gitpod.io/#https://github.com/pgmate/demo)

## Run it as GitHub CodeSpace

If you are reading this document from our GitHub page, follow these instructions and run PGMate demo in the Cloud:

1. Click on: `Code`
2. Click on: `Create codespace on main`
3. Take a cup of coffee...

![github-codespaces](./pgmate-github-codespace.png)

A cloud-native development environment will open in a new tab and the project will be automatically initialized.

Within a couple of minutes, PGMate login page will open automatically.

## Clone and run it locally

```bash
# Clone the demo:
git clone https://gitpod.io/#https://github.com/pgmate/demo pgmate

# Run with Docker:
cd pgmate
docker compose up
```

## Login to PGMate

This demo environment starts with the default password: `pgmate`.

![PGMate Login](./pgmate-login.png)

Once you login, you can navigate the schema of the `Default Connection`:

![PGMate Home](./pgmate-home.png)

Open a table in `Data View`:

![PGMate Data](./pgmate-data.png)

Or export a table's DLL:

![PGMate DLL](./pgmate-dll.png)