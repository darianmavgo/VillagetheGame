config.yaml
----------------

Create `config.yaml`:

```
wallet:
  secret: yourgooglewalletsecret
  ident: yourgooglewalletident
  production: false

spreadsheet:
  login: "mail-of-user-which-has-access-to-config-spreadsheets@gmail.com"
  password: "password-for-that-user"
```

Deployment
-----------

Install pip and virtualenv. For example, on MacOSX:

```
sudo easy_install pip
sudo pip install virtualenv
```

Install Node.js and then IGE deps via NPM:

```
cd ige/server
npm install
```

Deploy:

```
./upload.sh
```