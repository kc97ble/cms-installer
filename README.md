# cms-installer

A script to install [CMS](https://github.com/cms-dev/cms) [1.3.2](https://cms.readthedocs.io/en/v1.3/) quickly.

## Usage

```
chmod a+x install.sh
./install install
```

Now CMS is installed.

```
source /usr/local/lib/cms/bin/activate
cmsInitDB
cmsAddAdmin -p 12345678 admin
cmsAdminWebServer
deactivate
```
