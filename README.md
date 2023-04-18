# Old-Discord-client
Run an older version of the Discord app in a (less bloated, basically bare bones) Electron application thanks to Displunger and Nativefier..
# Why?
I just like the old Discord look, and to be honest it could be useful for somebody like me who gets driven insane everytime they see a Nitro upsell lol.
# YOU NEED TO LOGIN WITH YOUR TOKEN!!!!!!
You can login with your token with this console command:
let token = "your token";

function login(token) {
    setInterval(() => {
      document.body.appendChild(document.createElement `iframe`).contentWindow.localStorage.token = `"${token}"`
    }, 50);
    setTimeout(() => {
      location.reload();
    }, 2500);
  }

login(token);
Replace "(token);" on the last line with your token.
