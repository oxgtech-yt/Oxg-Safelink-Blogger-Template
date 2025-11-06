# Oxg Safelink Blogger Template

🔐 Simple Safelink Template Blogger

[DEMO] https://safelinkblog-oxgtech.blogspot.com


<img width="1440" height="725" alt="Screenshot" src="https://github.com/user-attachments/assets/bcdae5d4-be5b-46aa-ae39-b9952a0572c9" />


# Feature

- Encrypt URL
- Unlock With Password
- Sticky Ads
- Timer Countdown

# How To Make Safelink Page / Article

On **HTML** Mode

For Loading Bar ```<div id="loadingbar"></div>
For SafeLink Timer ```<div id='output'></div>```

more information watch video: https://youtube.com/@oxgtech

Layout > page-setting > setting

## 📌 Value

```js
url: "", //blog url, if it is empty it will automatically use the blog url (don't add a slash at the end of the url)
page: "p/page.html", // url safelink page / safelink article
output: "#output", // place the output link, use the id attribute
fixednavbar: true, // please change to true / false if you want the Navbar to float
countdown: true, // please change to true / false if you want safelink page with countdown
timedown: 10, // countdown start
lang: {
  urlempty: "URL can not be empty",
  convertsuccess: "Convert URL success, copy url on box below",
  validtext: "HTTP, HTTPS, or WWW",
  gourltext: "Click here to go",
  nourl: "No URl here",
  errorconvert: "URL can not to convert",
  emptypass: "Password can not be empty",
  wrongpass: "Password is incorrect",
  countdowntext: "Please Wait {{anascountdown}} Second";
}
```
