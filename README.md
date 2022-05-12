# locker-myapps-static

Static website files for [locker-myapps](https://github.com/yaroslaff/locker-myapps)

# Quickstart

Clone repo:
`git clone https://github.com/yaroslaff/locker-myapps.git`

create `_config.js` file with address registerd for your myapps application at locker server:
~~~
locker_addr = 'myapps.l.www-security.com';
~~~

# Forking this repo
Note, `_config.js` and `CNAME` files are listed in `.gitignore`, so if you want to fork this repo for your project, edit .gitignore too.

# Deployment examples (options)

## Deploy to surge/cloudflare
If you want to use [surge.sh](https://surge.sh/) for hosting (easy wasy), [install surge](https://surge.sh/help/getting-started-with-surge) and upload with `surge` command. Then add [custom domain](https://surge.sh/help/adding-a-custom-domain) using cloudflare as DNS service (CNAME which forwards to surge server).

# Credits / Links
- https://github.com/estevanmaito/windmill-dashboard 
- https://windmillui.com/dashboard-html