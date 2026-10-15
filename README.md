# StyleNest (practice shop)

A static fashion shop built with plain HTML, CSS and JavaScript, used as a Selenium practice site.
All brands, products and prices are made up. Nothing is sent to a server.

- Pages live in `site/`. There is no build step.
- Deploy: Render Static Site, Build Command `echo "static site"`, Publish Directory `site`.
- Slow mode switches on only when a test tool drives the browser. Add `?auto=1` to try it by hand, `?auto=0` to switch it off.
- Test values: coupons `STYLE10`, `NEST20`, `FREESHIP`; wrong password `wrongpass`; demo orders `SN-10458`, `SN-10459`, `SN-10462`; declined card `4000 0000 0000 0002`; failing UPI `fail@upi`.
