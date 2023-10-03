# Employee Onboarding 

## Before Employee Starts

### Zitadel

1. https://login.freedomtech.hosting/ui/console/users
2. Click `New`
3. Fill out Infos
    - `E-mail`: firstname.lastname@freedomtech.hosting
    - `Username`: firstname.lastname@freedomtech.hosting
    - `Given Name`: Firstname
    - `Family Name`: Lastname
    - `Nickname`: leave empty
    - `Email verified`: Check
    - `Set Initial Password`: Check
        - Create and store password
    - `Other Fields`: Leave empty
4. Click `Create`


### Google

1. https://admin.google.com/ac/users?hl=en
2. Click `Add new user`
3. Fill out infos:
    - `First name`: Firstname
    - `Last name`: Lastname
    - `Primary email`: firstname.lastname@freedomtech.hosting
    - `Other Fields`: Leave empty
4. Click `Add new user` (no need to store password)


### Slack

Nothing to configure, happens fully automatically on first login.

### Bitwarden

Configuration happens on first day.


## On first day

### Zitadel

1. User goes to https://login.freedomtech.hosting/ and logs in with created password during setup
2. User sets up MFA

### Google

1. Go to mail.google.com and Login with firstname.lastname@freedomtech.hosting via Zitadel

### Slack

1. Go to https://freedomtechhosting.slack.com and login via Zitadel


### Bitwarden

1. User logs in at https://vault.bitwarden.eu
    - User account is automatically created, user will create master password
2. Go to https://vault.bitwarden.eu/#/organizations/a5f5b39a-5117-493c-a2c7-b06201153c6b/members
3. Click `Confirm`, check with user that `encryption keys` matches
4. Click `Confirm`