# bootcamp-authentication-secrets

Fork of App Brewery's companion code for the **Authentication & Security** module of The Complete Web Development Bootcamp. "Secrets" is a small app where users sign up, log in and post a secret anonymously.

**Status:** Learning archive (fork) · **Stack:** Node.js, Express, EJS, MongoDB/Mongoose, Passport.js

## What the module covers

The upstream history walks through six levels of authentication, one commit per lesson:

1. Username and password stored in the database
2. Database encryption
3. Hashing passwords
4. Salting and hashing with bcrypt
5. Sessions and cookies with Passport.js
6. Third-party login with Google OAuth 2.0

Step through the lessons with `git log` and `git checkout <commit>`.

## Running

```bash
npm install
node app.js
```

Requires a running MongoDB instance and, for level 6, Google OAuth credentials in a `.env` file.

## Related

- [web-development-bootcamp](https://github.com/EmreKaram/web-development-bootcamp): the rest of my bootcamp work
