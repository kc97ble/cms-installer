# cms-installer

A script to install [CMS](https://github.com/cms-dev/cms) [1.3.2](https://cms.readthedocs.io/en/v1.3/) quickly.

## Installation

```
chmod a+x install.sh
./install install
```

Now CMS is installed.

## Running CMS

```
source /usr/local/lib/cms/bin/activate
... # your commands here
deactivate
```

For example,

```
source /usr/local/lib/cms/bin/activate
cmsInitDB
cmsAddAdmin -p 12345678 admin
cmsAdminWebServer
# Now visit localhost:8889, you should see the admin page.
deactivate
```
