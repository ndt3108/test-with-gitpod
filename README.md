[![Gitpod Ready-to-Code](https://img.shields.io/badge/Gitpod-Ready--to--Code-blue?logo=gitpod)](https://gitpod.io/#https://github.com/trinhpham/test-with-gitpod) 

# TestArchitect Gondola Workshop

## Getting Started
- Create TA Gondola account: https://sso.logigear.com/register/?host_url=https://gondolatest.com/en/thankyou/&_ga=2.28415100.1139009272.1605894476-1871157089.1576096278
- Create Github account: https://github.com/
## Launching Gondola
- Go to https://gitpod.io/#https://github.com/trinhpham/test-with-gitpod and click on 'Login with GitHub & Launch Workspace"
- Use your GitHub account to login and wait for Gitpod to get Gondola ready. It's ready when you see VS Code loaded.
- When asked, allow the noVNC popup be opened and enter `secret` as the VNC password. (If you miss this step, see the port 6080 at bottom, click on it then click on `Open Browser` on the opened panel). Highly recommend opening the VNC page in browser.
- [Enable beta feataures](https://docs.gondolatest.com/guides/beta-features.html#enabling-beta-features) (Note: this step is going to be eliminated)
## Run Test
- [Generate a Gondola token](https://docs.gondolatest.com/subscription/#generating-a-token)
- Open package.json, then add --licenseToken for "test" script. Example: "test": "./node_modules/.bin/gondola run --steps --reporter mochawesome --licenseToken ABCDEFDSFASDFASDFASDFASD"
- Run your test with `npm run test` and see how it runs on the VNC page.
## Record A Test
...
## Execute Test
- Execute
- Watch test execution through VNC connection
## Execute Test on BrowserStack
Note: BrowserStack accepts emails like gmail
- Setup
- Parallel test execution on Windows & Mac
- Parallel test execution on Android devices

