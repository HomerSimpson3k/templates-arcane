# ByteStash

## Activate OIDC

To activate OIDC follow the [setup instructions](https://github.com/jordan-dalby/ByteStash/wiki/Single-Sign%E2%80%90on-Setup) and set the according variables in `.env` file.

## Generate secret token

Add a `JWT_SECRET`. You can create a random token by running:

```bash
openssl rand -base64 32
```

in your command line. You can alternatively set a `JWT_SECRET_FILE`.

## Add admin users

When accessing the app for the first time you will have to create a user. You can add the username (or multiple usernames separated by comma) in `ADMIN_USERNAMES` to allow this user(s) to access the `Admin panel`.

## Env variables

To learn more about the configurable environment variables you can visit [ByteStash's FAQ site](https://github.com/jordan-dalby/ByteStash/wiki/FAQ#environment-variables).
