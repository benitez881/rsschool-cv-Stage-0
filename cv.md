## **Kostrov Pavel**

### **My contacts**

* Telegram: [benitzz](https://t.me/benitzz)
* Email: [pashakostrov.pk@gmail.com](pashakostrov.pk@gmail.com)
* Kherson/Odessa, Ukraine

### **About me**

Hello, I've been studying the frontend since August 2021. I am also a first-year student of the university majoring in software developer.

## **My Skills**

* HTML5
* CSS3
* JS basic
* Git&Github
* BEM
* SCSS

## **Code examples**

Write a function that when given a URL as a string, parses out just the domain name and returns it as a string. For example:

domainName("http://github.com/carbonfive/raygun") == "github" 
domainName("http://www.zombie-bites.com") == "zombie-bites"
domainName("https://www.cnet.com") == "cnet"
```
function domainName(url){
  let res = ''
  if(url.includes('//')) {
    let urlWithoutSlash = url.slice(url.indexOf('//') + 2)
    if(urlWithoutSlash.startsWith('www')) {
      let urlWithoutWWW = url.slice(url.indexOf('www') + 4)
      res = urlWithoutWWW.substring(0, urlWithoutWWW.indexOf('.'))
    } else {
      res = urlWithoutSlash.substring(0, urlWithoutSlash.indexOf('.'))}
  } else if(url.startsWith('www')) {
      let urlWithoutWWW = url.slice(url.indexOf('www') + 4)
      res = urlWithoutWWW.substring(0, urlWithoutWWW.indexOf('.'))
  } else {
    res = url.substring(0, url.indexOf('.'))
  }
  return res
}
```

## **My education**

1. Kherson school №1
1. National University "Odessa Polytechnic"(enrolled in 2021)

## **Languages**

* Ukrainian(Native)
* Russian(Native)
* English(A2+/B1)