# autofb
Testing autofb from UiPath
{
  "Name": "11521",
  "CreationDate": "2021-5-25",
  "Commands": [
    {
      "Command": "comment",
      "Target": "open // ${!cmd_var1}",
      "Value": "",
      "Description": ""
    },
    {
      "Command": "store",
      "Target": "${!cmd_var1}",
      "Value": "recordId",
      "Description": ""
    },
    {
      "Command": "comment",
      "Target": "executeScript_Sandbox // return  Math.floor(Math.random() * 20) + 1",
      "Value": "recordId",
      "Description": ""
    },
    {
      "Command": "store",
      "Target": "15",
      "Value": "recordId",
      "Description": ""
    },
    {
      "Command": "comment",
      "Target": "open // ${!cmd_var2}",
      "Value": "",
      "Description": ""
    },
    {
      "Command": "store",
      "Target": "${!cmd_var2}",
      "Value": "DomainIp",
      "Description": ""
    },
    {
      "Command": "echo",
      "Target": "${!cmd_var2}",
      "Value": "",
      "Description": ""
    },
    {
      "Command": "comment",
      "Target": "open // ${!cmd_var3}",
      "Value": "",
      "Description": ""
    },
    {
      "Command": "store",
      "Target": "${!cmd_var3}",
      "Value": "DomainPort",
      "Description": ""
    },
    {
      "Command": "comment",
      "Target": "open // ${!cmd_var4}",
      "Value": "password",
      "Description": ""
    },
    {
      "Command": "comment",
      "Target": "open // ${!cmd_var5}",
      "Value": "emailbackup",
      "Description": ""
    },
    {
      "Command": "comment",
      "Target": "open // ${!cmd_var6}",
      "Value": "phoneNumber",
      "Description": ""
    },
    {
      "Command": "comment",
      "Target": "open // ${!cmd_var3}",
      "Value": "proxy",
      "Description": ""
    },
    {
      "Command": "comment",
      "Target": "open // ${!cmd_var8}",
      "Value": "proxtUser",
      "Description": ""
    },
    {
      "Command": "comment",
      "Target": "open // ${!cmd_var9}",
      "Value": "proxyPass",
      "Description": ""
    },
    {
      "Command": "comment",
      "Target": "store // ${!cmd_var10}",
      "Value": "isLikeVideo",
      "Description": ""
    },
    {
      "Command": "comment",
      "Target": "store // ${!cmd_var10}",
      "Value": "isLikeVideo",
      "Description": ""
    },
    {
      "Command": "comment",
      "Target": "store // ${!cmd_var11}",
      "Value": "txtComent",
      "Description": ""
    },
    {
      "Command": "comment",
      "Target": "store // ${!cmd_var12}",
      "Value": "txtTimeWatchVideo",
      "Description": ""
    },
    {
      "Command": "comment",
      "Target": "store // ${!cmd_var13}",
      "Value": "txtTimeWatchVideo",
      "Description": ""
    },
    {
      "Command": "comment",
      "Target": "store // ${!cmd_var14}",
      "Value": "listVideoKeywords",
      "Description": ""
    },
    {
      "Command": "comment",
      "Target": "store // ${!cmd_var15}",
      "Value": "txtVideoId",
      "Description": ""
    },
    {
      "Command": "comment",
      "Target": "store // ${!cmd_var16}",
      "Value": "listUrl",
      "Description": ""
    },
    {
      "Command": "comment",
      "Target": "echo // ${recordId}",
      "Value": "${!cmd_var1}",
      "Description": ""
    },
    {
      "Command": "store",
      "Target": "-1",
      "Value": "status",
      "Description": ""
    },
    {
      "Command": "store",
      "Target": "",
      "Value": "errorMessage",
      "Description": ""
    },
    {
      "Command": "store",
      "Target": "0",
      "Value": "actionStatus",
      "Description": ""
    },
    {
      "Command": "store",
      "Target": "true",
      "Value": "!errorignore",
      "Description": ""
    },
    {
      "Command": "open",
      "Target": "http://${DomainIp}:${DomainPort}/AccountExecute/GetNewExecuteRecord?recordId=${recordId}",
      "Value": "",
      "Description": ""
    },
    {
      "Command": "comment",
      "Target": "setProxy // socks5://183.80.18.217:2222",
      "Value": "",
      "Description": ""
    },
    {
      "Command": "pause",
      "Target": "1000",
      "Value": "",
      "Description": ""
    },
    {
      "Command": "setWindowSize",
      "Target": "385x720",
      "Value": "",
      "Description": ""
    },
    {
      "Command": "comment",
      "Target": "setWindowSize // 1024x720",
      "Value": "",
      "Description": ""
    },
    {
      "Command": "comment",
      "Target": "deleteAllCookies // ",
      "Value": "",
      "Description": ""
    },
    {
      "Command": "storeText",
      "Target": "id=recordId",
      "Value": "recordId",
      "Description": ""
    },
    {
      "Command": "storeText",
      "Target": "id=email",
      "Value": "email",
      "Description": ""
    },
    {
      "Command": "comment",
      "Target": "storeText // id=proxyType",
      "Value": "proxyType",
      "Description": ""
    },
    {
      "Command": "storeText",
      "Target": "id=password",
      "Value": "password",
      "Description": ""
    },
    {
      "Command": "storeText",
      "Target": "id=emailbackup",
      "Value": "emailbackup",
      "Description": ""
    },
    {
      "Command": "storeText",
      "Target": "id=phoneNumber",
      "Value": "phoneNumber",
      "Description": ""
    },
    {
      "Command": "comment",
      "Target": "storeText // id=proxy",
      "Value": "proxy",
      "Description": ""
    },
    {
      "Command": "comment",
      "Target": "storeText // id=proxtUser",
      "Value": "proxtUser",
      "Description": ""
    },
    {
      "Command": "comment",
      "Target": "storeText // id=proxyPass",
      "Value": "proxyPass",
      "Description": ""
    },
    {
      "Command": "storeText",
      "Target": "id=proxyType",
      "Value": "proxyType",
      "Description": ""
    },
    {
      "Command": "storeText",
      "Target": "id=isLikeVideo",
      "Value": "isLikeVideo",
      "Description": ""
    },
    {
      "Command": "storeText",
      "Target": "id=txtComent",
      "Value": "txtComent",
      "Description": ""
    },
    {
      "Command": "storeText",
      "Target": "id=txtTimeWatchVideo",
      "Value": "txtTimeWatchVideo",
      "Description": ""
    },
    {
      "Command": "storeText",
      "Target": "id=listVideoKeywords",
      "Value": "listVideoKeywords",
      "Description": ""
    },
    {
      "Command": "storeText",
      "Target": "id=txtVideoId",
      "Value": "txtVideoId",
      "Description": ""
    },
    {
      "Command": "storeText",
      "Target": "id=listUrl",
      "Value": "listUrl",
      "Description": ""
    },
    {
      "Command": "comment",
      "Target": "storeText // id=txtChanel",
      "Value": "txtChanel",
      "Description": ""
    },
    {
      "Command": "comment",
      "Target": "storeText // id=txtChanelDes",
      "Value": "txtChanelDes",
      "Description": ""
    },
    {
      "Command": "comment",
      "Target": "storeText // id=txtUrlWeb",
      "Value": "txtUrlWeb",
      "Description": ""
    },
    {
      "Command": "comment",
      "Target": "storeText // id=txtFacebookProfileName",
      "Value": "txtFacebookProfileName",
      "Description": ""
    },
    {
      "Command": "comment",
      "Target": "storeText // id=txtTwitterProfileName",
      "Value": "txtTwitterProfileName",
      "Description": ""
    },
    {
      "Command": "comment",
      "Target": "storeText // id=txtInstagramProfileName",
      "Value": "txtInstagramProfileName",
      "Description": ""
    },
    {
      "Command": "if_v2",
      "Target": "!${!statusOK} == true",
      "Value": "",
      "Description": ""
    },
    {
      "Command": "store",
      "Target": "-1",
      "Value": "status",
      "Description": ""
    },
    {
      "Command": "store",
      "Target": " proxy die",
      "Value": "errorMessage",
      "Description": ""
    },
    {
      "Command": "captureEntirePageScreenshot",
      "Target": "${recordId}- ${errorMessage}",
      "Value": "",
      "Description": ""
    },
    {
      "Command": "gotoLabel",
      "Target": "THROW_EXCEPTION",
      "Value": "",
      "Description": ""
    },
    {
      "Command": "end",
      "Target": "",
      "Value": "",
      "Description": ""
    },
    {
      "Command": "deleteAllCookies",
      "Target": "",
      "Value": "",
      "Description": ""
    },
    {
      "Command": "executeScript_Sandbox",
      "Target": "var arrKeyWord =   ${listVideoKeywords}.toString().split(\"\\n\").filter(item => item !=0 && item.trim != '' && item != null && item);\n\nreturn arrKeyWord;",
      "Value": "arrVideoKeywords",
      "Description": ""
    },
    {
      "Command": "if_v2",
      "Target": "${arrVideoKeywords.length} == 0",
      "Value": "",
      "Description": ""
    },
    {
      "Command": "store",
      "Target": "6",
      "Value": "status",
      "Description": ""
    },
    {
      "Command": "store",
      "Target": "Khong co keyword",
      "Value": "errorMessage",
      "Description": ""
    },
    {
      "Command": "captureEntirePageScreenshot",
      "Target": "${recordId}- ${errorMessage}",
      "Value": "",
      "Description": ""
    },
    {
      "Command": "gotoLabel",
      "Target": "THROW_EXCEPTION",
      "Value": "",
      "Description": ""
    },
    {
      "Command": "end",
      "Target": "${arrVideoKeywords}.Count == 0",
      "Value": "",
      "Description": ""
    },
    {
      "Command": "if_v2",
      "Target": "${listUrl}.length >5",
      "Value": "",
      "Description": ""
    },
    {
      "Command": "executeScript_Sandbox",
      "Target": "return  ${listUrl}.toString().split(\"\\n\");",
      "Value": "arrUrl",
      "Description": ""
    },
    {
      "Command": "forEach",
      "Target": "arrUrl",
      "Value": "itemUrl",
      "Description": ""
    },
    {
      "Command": "open",
      "Target": "${itemUrl}",
      "Value": "",
      "Description": ""
    },
    {
      "Command": "pause",
      "Target": "2000",
      "Value": "",
      "Description": ""
    },
    {
      "Command": "executeAsyncScript",
      "Target": "window.scrollBy(0,200);",
      "Value": "",
      "Description": ""
    },
    {
      "Command": "pause",
      "Target": "3000",
      "Value": "",
      "Description": ""
    },
    {
      "Command": "end",
      "Target": "",
      "Value": "",
      "Description": ""
    },
    {
      "Command": "end",
      "Target": "",
      "Value": "",
      "Description": ""
    },
    {
      "Command": "store",
      "Target": "true",
      "Value": "!statusOK",
      "Description": ""
    },
    {
      "Command": "open",
      "Target": "https://www.google.com/",
      "Value": "",
      "Description": ""
    },
    {
      "Command": "pause",
      "Target": "2000",
      "Value": "",
      "Description": ""
    },
    {
      "Command": "executeAsyncScript",
      "Target": "window.scrollBy(0,200);",
      "Value": "",
      "Description": ""
    },
    {
      "Command": "open",
      "Target": "https://accounts.google.com/signin/v2/identifier?hl=en&passive=true&continue=https%3A%2F%2Fwww.google.com.vn%2Fimghp%3Fhl%3Dvi%26amp%3Bogbl%26pli%3D1&ec=GAZAAg&flowName=GlifWebSignIn&flowEntry=ServiceLogin",
      "Value": "",
      "Description": ""
    },
    {
      "Command": "pause",
      "Target": "2000",
      "Value": "",
      "Description": ""
    },
    {
      "Command": "type",
      "Target": "id=identifierId",
      "Value": "${email}",
      "Description": ""
    },
    {
      "Command": "click",
      "Target": "xpath=//div[@id='identifierNext']",
      "Value": "",
      "Description": ""
    },
    {
      "Command": "comment",
      "Target": "doubleClick // xpath=//input[@name='password']",
      "Value": "",
      "Description": ""
    },
    {
      "Command": "pause",
      "Target": "2000",
      "Value": "",
      "Description": ""
    },
    {
      "Command": "type",
      "Target": "xpath=//input[@name='password']",
      "Value": "${password}",
      "Description": ""
    },
    {
      "Command": "pause",
      "Target": "2000",
      "Value": "",
      "Description": ""
    },
    {
      "Command": "click",
      "Target": "xpath=//div[@id='passwordNext']",
      "Value": "",
      "Description": ""
    },
    {
      "Command": "verifyElementNotPresent",
      "Target": "id=identifierId",
      "Value": "",
      "Description": ""
    },
    {
      "Command": "if_v2",
      "Target": "!${!statusOK} == true",
      "Value": "",
      "Description": ""
    },
    {
      "Command": "store",
      "Target": "true",
      "Value": "!statusOK",
      "Description": ""
    },
    {
      "Command": "type",
      "Target": "id=identifierId",
      "Value": "${email}",
      "Description": ""
    },
    {
      "Command": "pause",
      "Target": "2000",
      "Value": "",
      "Description": ""
    },
    {
      "Command": "click",
      "Target": "xpath=//div[@id='identifierNext']",
      "Value": "",
      "Description": ""
    },
    {
      "Command": "pause",
      "Target": "2000",
      "Value": "",
      "Description": ""
    },
    {
      "Command": "type",
      "Target": "xpath=//input[@name='password']",
      "Value": "${password}",
      "Description": ""
    },
    {
      "Command": "click",
      "Target": "xpath=//div[@id='passwordNext']",
      "Value": "",
      "Description": ""
    },
    {
      "Command": "verifyElementNotPresent",
      "Target": "id=identifierId",
      "Value": "",
      "Description": ""
    },
    {
      "Command": "if_v2",
      "Target": "!${!statusOK} == true",
      "Value": "",
      "Description": ""
    },
    {
      "Command": "gotoLabel",
      "Target": "LOGIN_FALSE",
      "Value": "",
      "Description": ""
    },
    {
      "Command": "end",
      "Target": "",
      "Value": "",
      "Description": ""
    },
    {
      "Command": "end",
      "Target": "",
      "Value": "",
      "Description": ""
    },
    {
      "Command": "if_v2",
      "Target": "!${!statusOK} == true",
      "Value": "",
      "Description": ""
    },
    {
      "Command": "label",
      "Target": "LOGIN_FALSE",
      "Value": "",
      "Description": ""
    },
    {
      "Command": "store",
      "Target": "0",
      "Value": "status",
      "Description": ""
    },
    {
      "Command": "store",
      "Target": "login false",
      "Value": "errorMessage",
      "Description": ""
    },
    {
      "Command": "captureEntirePageScreenshot",
      "Target": "${recordId}- ${errorMessage}",
      "Value": "",
      "Description": ""
    },
    {
      "Command": "gotoLabel",
      "Target": "THROW_EXCEPTION",
      "Value": "",
      "Description": ""
    },
    {
      "Command": "end",
      "Target": "",
      "Value": "",
      "Description": ""
    },
    {
      "Command": "store",
      "Target": "true",
      "Value": "!statusOK",
      "Description": ""
    },
    {
      "Command": "verifyElementPresent",
      "Target": "xpath=//div[@aria-haspopup=\"listbox\" and @role=\"combobox\" and @aria-expanded=\"false\" ]",
      "Value": "",
      "Description": ""
    },
    {
      "Command": "if_v2",
      "Target": "${!statusOK} == true",
      "Value": "",
      "Description": ""
    },
    {
      "Command": "click",
      "Target": "xpath=//div[@aria-haspopup=\"listbox\" and @role=\"combobox\" and @aria-expanded=\"false\" ]",
      "Value": "",
      "Description": ""
    },
    {
      "Command": "click",
      "Target": "xpath=//span[text()=\"January\"]",
      "Value": "",
      "Description": ""
    },
    {
      "Command": "pause",
      "Target": "1000",
      "Value": "",
      "Description": ""
    },
    {
      "Command": "click",
      "Target": "xpath=//input[@placeholder=\"DD\"]",
      "Value": "",
      "Description": ""
    },
    {
      "Command": "type",
      "Target": "xpath=//input[@placeholder=\"DD\"]",
      "Value": "1",
      "Description": ""
    },
    {
      "Command": "pause",
      "Target": "500",
      "Value": "",
      "Description": ""
    },
    {
      "Command": "click",
      "Target": "xpath=//input[@placeholder=\"YYYY\"]",
      "Value": "",
      "Description": ""
    },
    {
      "Command": "type",
      "Target": "xpath=//input[@placeholder=\"YYYY\"]",
      "Value": "2001",
      "Description": ""
    },
    {
      "Command": "pause",
      "Target": "1000",
      "Value": "",
      "Description": ""
    },
    {
      "Command": "executeAsyncScript",
      "Target": "window.scrollBy(0,200);",
      "Value": "",
      "Description": ""
    },
    {
      "Command": "click",
      "Target": "xpath=//button[contains(@jsaction,\"click\")]//child::span",
      "Value": "",
      "Description": ""
    },
    {
      "Command": "pause",
      "Target": "1000",
      "Value": "",
      "Description": ""
    },
    {
      "Command": "click",
      "Target": "xpath=//span[text()=\"Confirm\"]",
      "Value": "",
      "Description": ""
    },
    {
      "Command": "end",
      "Target": "",
      "Value": "",
      "Description": ""
    },
    {
      "Command": "pause",
      "Target": "5000",
      "Value": "",
      "Description": ""
    },
    {
      "Command": "store",
      "Target": "true",
      "Value": "!statusOK",
      "Description": ""
    },
    {
      "Command": "open",
      "Target": "https://www.youtube.com/",
      "Value": "",
      "Description": ""
    },
    {
      "Command": "pause",
      "Target": "5000",
      "Value": "",
      "Description": ""
    },
    {
      "Command": "store",
      "Target": "0",
      "Value": "intCheckCookie",
      "Description": ""
    },
    {
      "Command": "executeScript_Sandbox",
      "Target": "  var getting = browser.cookies.get({\n    url: \"youtube.com\",\n    name: \"LOGIN_INFO\"\n  });\nif(getting != null){\n  return 1;\n}else return 0",
      "Value": "intCheckCookie",
      "Description": ""
    },
    {
      "Command": "if_v2",
      "Target": "${intCheckCookie} == 0",
      "Value": "",
      "Description": ""
    },
    {
      "Command": "refresh",
      "Target": "",
      "Value": "",
      "Description": ""
    },
    {
      "Command": "pause",
      "Target": "2000",
      "Value": "",
      "Description": ""
    },
    {
      "Command": "end",
      "Target": "",
      "Value": "",
      "Description": ""
    },
    {
      "Command": "executeScript_Sandbox",
      "Target": "  var getting = browser.cookies.get({\n    url: \"youtube.com\",\n    name: \"LOGIN_INFO\"\n  });\nif(getting != null){\n  return 1;\n}else return 0",
      "Value": "intCheckCookie",
      "Description": ""
    },
    {
      "Command": "if_v2",
      "Target": "${intCheckCookie} == 0",
      "Value": "",
      "Description": ""
    },
    {
      "Command": "store",
      "Target": "0",
      "Value": "status",
      "Description": ""
    },
    {
      "Command": "store",
      "Target": "Khong co cookie",
      "Value": "errorMessage",
      "Description": ""
    },
    {
      "Command": "captureEntirePageScreenshot",
      "Target": "${recordId}- ${errorMessage}",
      "Value": "",
      "Description": ""
    },
    {
      "Command": "gotoLabel",
      "Target": "THROW_EXCEPTION",
      "Value": "",
      "Description": ""
    },
    {
      "Command": "end",
      "Target": "",
      "Value": "",
      "Description": ""
    },
    {
      "Command": "clickAndWait",
      "Target": "id=img",
      "Value": "",
      "Description": ""
    },
    {
      "Command": "pause",
      "Target": "2000",
      "Value": "",
      "Description": ""
    },
    {
      "Command": "storeText",
      "Target": "id=primary-text-container",
      "Value": "strLanguage",
      "Description": ""
    },
    {
      "Command": "executeScript_Sandbox",
      "Target": "return ${strLanguage}.includes(\"English\")",
      "Value": "IsEnglish",
      "Description": ""
    },
    {
      "Command": "if_v2",
      "Target": "${IsEnglish} != true",
      "Value": "",
      "Description": ""
    },
    {
      "Command": "store",
      "Target": "Not english language",
      "Value": "errorMessage",
      "Description": ""
    },
    {
      "Command": "store",
      "Target": "3",
      "Value": "status",
      "Description": ""
    },
    {
      "Command": "end",
      "Target": "",
      "Value": "",
      "Description": ""
    },
    {
      "Command": "executeAsyncScript",
      "Target": "window.scrollBy(0,200);",
      "Value": "",
      "Description": ""
    },
    {
      "Command": "pause",
      "Target": "1000",
      "Value": "",
      "Description": ""
    },
    {
      "Command": "executeScript",
      "Target": "window.scrollBy(0,200);",
      "Value": "",
      "Description": ""
    },
    {
      "Command": "pause",
      "Target": "1000",
      "Value": "",
      "Description": ""
    },
    {
      "Command": "store",
      "Target": "0",
      "Value": "blSearch",
      "Description": ""
    },
    {
      "Command": "forEach",
      "Target": "arrVideoKeywords",
      "Value": "itemVideo",
      "Description": ""
    },
    {
      "Command": "store",
      "Target": "true",
      "Value": "!statusOK",
      "Description": ""
    },
    {
      "Command": "click",
      "Target": "xpath=//input[@id='search']",
      "Value": "",
      "Description": ""
    },
    {
      "Command": "type",
      "Target": "xpath=//input[@id='search']",
      "Value": "${itemVideo}",
      "Description": ""
    },
    {
      "Command": "sendKeys",
      "Target": "xpath=//input[@id='search']",
      "Value": "${KEY_ENTER}",
      "Description": ""
    },
    {
      "Command": "pause",
      "Target": "3000",
      "Value": "",
      "Description": ""
    },
    {
      "Command": "verifyElementPresent",
      "Target": "xpath=//a[@class = 'yt-simple-endpoint style-scope ytd-video-renderer' and contains(@href,\"${itemVideo}\")]",
      "Value": "",
      "Description": ""
    },
    {
      "Command": "if_v2",
      "Target": "${!statusOK}",
      "Value": "",
      "Description": ""
    },
    {
      "Command": "click",
      "Target": "xpath=//a[@class = 'yt-simple-endpoint style-scope ytd-video-renderer' and contains(@href,\"${itemVideo}\")]",
      "Value": "",
      "Description": ""
    },
    {
      "Command": "pause",
      "Target": "3000",
      "Value": "",
      "Description": ""
    },
    {
      "Command": "store",
      "Target": "1",
      "Value": "blSearch",
      "Description": ""
    },
    {
      "Command": "store",
      "Target": "1",
      "Value": "status",
      "Description": ""
    },
    {
      "Command": "gotoLabel",
      "Target": "SEACH_COMPLETE",
      "Value": "",
      "Description": ""
    },
    {
      "Command": "end",
      "Target": "",
      "Value": "",
      "Description": ""
    },
    {
      "Command": "end",
      "Target": "",
      "Value": "",
      "Description": ""
    },
    {
      "Command": "if_v2",
      "Target": "${blSearch} != 1",
      "Value": "",
      "Description": ""
    },
    {
      "Command": "store",
      "Target": "3",
      "Value": "status",
      "Description": ""
    },
    {
      "Command": "store",
      "Target": "not search",
      "Value": "errorMessage",
      "Description": ""
    },
    {
      "Command": "captureEntirePageScreenshot",
      "Target": "${recordId}- ${errorMessage}",
      "Value": "",
      "Description": ""
    },
    {
      "Command": "gotoLabel",
      "Target": "THROW_EXCEPTION",
      "Value": "",
      "Description": ""
    },
    {
      "Command": "end",
      "Target": "",
      "Value": "",
      "Description": ""
    },
    {
      "Command": "label",
      "Target": "SEACH_COMPLETE",
      "Value": "",
      "Description": ""
    },
    {
      "Command": "while_v2",
      "Target": "${!statusOK} == true",
      "Value": "",
      "Description": ""
    },
    {
      "Command": "XClick",
      "Target": "xpath=//button[@class=\"ytp-play-button ytp-button\"]",
      "Value": "",
      "Description": ""
    },
    {
      "Command": "pause",
      "Target": "3000",
      "Value": "",
      "Description": ""
    },
    {
      "Command": "verifyElementPresent",
      "Target": "xpath=//button[@class=\"ytp-play-button ytp-button\"]",
      "Value": "",
      "Description": ""
    },
    {
      "Command": "if_v2",
      "Target": "${!statusOK} == true",
      "Value": "",
      "Description": ""
    },
    {
      "Command": "storeAttribute",
      "Target": "xpath=//button[@class=\"ytp-play-button ytp-button\"]@aria-label",
      "Value": "val1",
      "Description": ""
    },
    {
      "Command": "click",
      "Target": "xpath=//button[@class=\"ytp-play-button ytp-button\"]",
      "Value": "",
      "Description": ""
    },
    {
      "Command": "pause",
      "Target": "1000",
      "Value": "",
      "Description": ""
    },
    {
      "Command": "storeAttribute",
      "Target": "xpath=//button[@class=\"ytp-play-button ytp-button\"]@aria-label",
      "Value": "val2",
      "Description": ""
    },
    {
      "Command": "if_v2",
      "Target": "${val1} !=${val2}",
      "Value": "",
      "Description": ""
    },
    {
      "Command": "gotoLabel",
      "Target": "ISPLAY",
      "Value": "",
      "Description": ""
    },
    {
      "Command": "end",
      "Target": "",
      "Value": "",
      "Description": ""
    },
    {
      "Command": "else",
      "Target": "",
      "Value": "",
      "Description": ""
    },
    {
      "Command": "gotoLabel",
      "Target": "ISPLAY",
      "Value": "",
      "Description": ""
    },
    {
      "Command": "end",
      "Target": "",
      "Value": "",
      "Description": ""
    },
    {
      "Command": "end",
      "Target": "",
      "Value": "",
      "Description": ""
    },
    {
      "Command": "label",
      "Target": "ISPLAY",
      "Value": "",
      "Description": ""
    },
    {
      "Command": "store",
      "Target": "true",
      "Value": "!statusOK",
      "Description": ""
    },
    {
      "Command": "pause",
      "Target": "6000",
      "Value": "",
      "Description": ""
    },
    {
      "Command": "comment",
      "Target": "verifyElementPresent // xpath=//*[contains(@id,\"ad-text\")]",
      "Value": "",
      "Description": ""
    },
    {
      "Command": "while_v2",
      "Target": "${!statusOK} == true",
      "Value": "",
      "Description": ""
    },
    {
      "Command": "verifyElementPresent",
      "Target": "xpath=//button[@class=\"ytp-ad-skip-button ytp-button\"]",
      "Value": "",
      "Description": ""
    },
    {
      "Command": "if_v2",
      "Target": "${!statusOK} == true",
      "Value": "",
      "Description": ""
    },
    {
      "Command": "click",
      "Target": "xpath=//button[@class=\"ytp-ad-skip-button ytp-button\"]",
      "Value": "",
      "Description": ""
    },
    {
      "Command": "else",
      "Target": "",
      "Value": "",
      "Description": ""
    },
    {
      "Command": "gotoLabel",
      "Target": "OUT_AD",
      "Value": "",
      "Description": ""
    },
    {
      "Command": "end",
      "Target": "",
      "Value": "",
      "Description": ""
    },
    {
      "Command": "end",
      "Target": "",
      "Value": "",
      "Description": ""
    },
    {
      "Command": "label",
      "Target": "OUT_AD",
      "Value": "",
      "Description": ""
    },
    {
      "Command": "store",
      "Target": "true",
      "Value": "!statusOK",
      "Description": ""
    },
    {
      "Command": "executeScript_Sandbox",
      "Target": "return ${txtTimeWatchVideo} * 1000",
      "Value": "txtTimeWatchVideo",
      "Description": ""
    },
    {
      "Command": "comment",
      "Target": "pause // ${txtTimeWatchVideo}",
      "Value": "",
      "Description": ""
    },
    {
      "Command": "store",
      "Target": "2",
      "Value": "actionStatus",
      "Description": ""
    },
    {
      "Command": "comment",
      "Target": "if_v2 // ${isLikeVideo} == true",
      "Value": "",
      "Description": ""
    },
    {
      "Command": "comment",
      "Target": "storeAttribute // xpath=//yt-icon-button[contains(@class,\"style-scope ytd-toggle-button-renderer style-default-active\")]",
      "Value": "",
      "Description": ""
    },
    {
      "Command": "verifyElementPresent",
      "Target": "xpath=//h1//following-sibling::div[@id=\"info\"]//child::ytd-toggle-button-renderer//child::button[starts-with(@aria-label,\"like this video\") and contains(@aria-pressed,\"false\")]",
      "Value": "",
      "Description": ""
    },
    {
      "Command": "if_v2",
      "Target": "${!statusOK} == true",
      "Value": "",
      "Description": ""
    },
    {
      "Command": "store",
      "Target": "1",
      "Value": "actionStatus",
      "Description": ""
    },
    {
      "Command": "click",
      "Target": "xpath=//h1//following-sibling::div[@id=\"info\"]//child::ytd-toggle-button-renderer//child::button[starts-with(@aria-label,\"like this video\") and contains(@aria-pressed,\"false\")]",
      "Value": "",
      "Description": ""
    },
    {
      "Command": "end",
      "Target": "",
      "Value": "",
      "Description": ""
    },
    {
      "Command": "comment",
      "Target": "click // css=.force-icon-button:nth-child(1) #button > #button > .style-scope",
      "Value": "",
      "Description": ""
    },
    {
      "Command": "store",
      "Target": "bài hát hay",
      "Value": "txtComent",
      "Description": ""
    },
    {
      "Command": "if_v2",
      "Target": "${txtComent}.length > 1",
      "Value": "",
      "Description": ""
    },
    {
      "Command": "executeScript",
      "Target": "window.scrollBy(0,200);",
      "Value": "",
      "Description": ""
    },
    {
      "Command": "pause",
      "Target": "2000",
      "Value": "",
      "Description": ""
    },
    {
      "Command": "executeScript",
      "Target": "window.scrollBy(0,200);",
      "Value": "",
      "Description": ""
    },
    {
      "Command": "pause",
      "Target": "3000",
      "Value": "",
      "Description": ""
    },
    {
      "Command": "executeScript",
      "Target": "var para= document.querySelector('body');\nvar compStyles = window.getComputedStyle(para);\nvar str = compStyles.getPropertyValue('width');\nreturn parseInt(str.slice(0,str.length));",
      "Value": "widthBrowser",
      "Description": ""
    },
    {
      "Command": "if_v2",
      "Target": "${widthBrowser} <1017",
      "Value": "",
      "Description": ""
    },
    {
      "Command": "executeScript",
      "Target": "window.scrollBy(0,400);",
      "Value": "",
      "Description": ""
    },
    {
      "Command": "pause",
      "Target": "2000",
      "Value": "",
      "Description": ""
    },
    {
      "Command": "executeScript",
      "Target": "window.scrollBy(0,300);",
      "Value": "",
      "Description": ""
    },
    {
      "Command": "pause",
      "Target": "2000",
      "Value": "",
      "Description": ""
    },
    {
      "Command": "executeScript",
      "Target": "window.scrollBy(0,400);",
      "Value": "",
      "Description": ""
    },
    {
      "Command": "pause",
      "Target": "2000",
      "Value": "",
      "Description": ""
    },
    {
      "Command": "executeScript",
      "Target": "window.scrollBy(0,350);",
      "Value": "",
      "Description": ""
    },
    {
      "Command": "pause",
      "Target": "2000",
      "Value": "",
      "Description": ""
    },
    {
      "Command": "executeScript",
      "Target": "window.scrollBy(0,500);",
      "Value": "",
      "Description": ""
    },
    {
      "Command": "pause",
      "Target": "2000",
      "Value": "",
      "Description": ""
    },
    {
      "Command": "end",
      "Target": "",
      "Value": "",
      "Description": ""
    },
    {
      "Command": "click",
      "Target": "id=placeholder-area",
      "Value": "",
      "Description": ""
    },
    {
      "Command": "editContent",
      "Target": "id=contenteditable-root",
      "Value": "${txtComent}",
      "Description": ""
    },
    {
      "Command": "click",
      "Target": "id=contenteditable-root",
      "Value": " ",
      "Description": ""
    },
    {
      "Command": "sendKeys",
      "Target": "id=contenteditable-root",
      "Value": "    111",
      "Description": ""
    },
    {
      "Command": "pause",
      "Target": "1000",
      "Value": "",
      "Description": ""
    },
    {
      "Command": "click",
      "Target": "xpath=//ytd-button-renderer[@id=\"submit-button\"]",
      "Value": "",
      "Description": ""
    },
    {
      "Command": "end",
      "Target": "",
      "Value": "",
      "Description": ""
    },
    {
      "Command": "pause",
      "Target": "1000",
      "Value": "",
      "Description": ""
    },
    {
      "Command": "store",
      "Target": "1",
      "Value": "txtChanel",
      "Description": ""
    },
    {
      "Command": "if_v2",
      "Target": "${txtChanel}.length <1",
      "Value": "",
      "Description": ""
    },
    {
      "Command": "store",
      "Target": "true",
      "Value": "!statusOK",
      "Description": ""
    },
    {
      "Command": "click",
      "Target": "id=img",
      "Value": "",
      "Description": ""
    },
    {
      "Command": "pause",
      "Target": "1000",
      "Value": "",
      "Description": ""
    },
    {
      "Command": "verifyElementPresent",
      "Target": "linktext =Create a channel",
      "Value": "",
      "Description": ""
    },
    {
      "Command": "if_v2",
      "Target": "${!statusOK} == true",
      "Value": "",
      "Description": ""
    },
    {
      "Command": "click",
      "Target": "linktext =Create a channel",
      "Value": "",
      "Description": ""
    },
    {
      "Command": "pause",
      "Target": "3000",
      "Value": "",
      "Description": ""
    },
    {
      "Command": "click",
      "Target": "linkText=Get started",
      "Value": "",
      "Description": ""
    },
    {
      "Command": "pause",
      "Target": "2000",
      "Value": "",
      "Description": ""
    },
    {
      "Command": "click",
      "Target": "xpath=//span[contains(@id,\"personal\")]",
      "Value": "",
      "Description": ""
    },
    {
      "Command": "pause",
      "Target": "2000",
      "Value": "",
      "Description": ""
    },
    {
      "Command": "executeAsyncScript",
      "Target": "window.scrollBy(0,500);",
      "Value": "",
      "Description": ""
    },
    {
      "Command": "click",
      "Target": "xpath=//*[@id=\"description-textarea\"]",
      "Value": "",
      "Description": ""
    },
    {
      "Command": "click",
      "Target": "xpath=//*[@id=\"description-textarea\"]",
      "Value": "",
      "Description": ""
    },
    {
      "Command": "type",
      "Target": "xpath=//*[@id=\"description-textarea\"]",
      "Value": "txtChanelDes",
      "Description": ""
    },
    {
      "Command": "executeAsyncScript",
      "Target": "window.scrollBy(0,300);",
      "Value": "",
      "Description": ""
    },
    {
      "Command": "click",
      "Target": "xpath=//*[@id=\"child-input\"]/div/input",
      "Value": "",
      "Description": ""
    },
    {
      "Command": "type",
      "Target": "xpath=//*[@id=\"child-input\"]/div/input",
      "Value": "txtUrlWeb",
      "Description": ""
    },
    {
      "Command": "executeAsyncScript",
      "Target": "window.scrollBy(0,200);",
      "Value": "",
      "Description": ""
    },
    {
      "Command": "click",
      "Target": "xpath=//*[@id=\"facebook-link\"]//input[@placeholder=\"add profile name\"]",
      "Value": "",
      "Description": ""
    },
    {
      "Command": "type",
      "Target": "xpath=//*[@id=\"facebook-link\"]//input[@placeholder=\"add profile name\"]",
      "Value": "txtFacebookProfileName",
      "Description": ""
    },
    {
      "Command": "executeAsyncScript",
      "Target": "window.scrollBy(0,200);",
      "Value": "",
      "Description": ""
    },
    {
      "Command": "click",
      "Target": "xpath=//*[@id=\"twitter-link\"]//input[@placeholder=\"add profile name\"]",
      "Value": "",
      "Description": ""
    },
    {
      "Command": "type",
      "Target": "xpath=//*[@id=\"twitter-link\"]//input[@placeholder=\"add profile name\"]",
      "Value": "txtTwitterProfileName",
      "Description": ""
    },
    {
      "Command": "pause",
      "Target": "1000",
      "Value": "",
      "Description": ""
    },
    {
      "Command": "click",
      "Target": "xpath=//*[@id=\"instagram-link\"]//input[@placeholder=\"add profile name\"]",
      "Value": "",
      "Description": ""
    },
    {
      "Command": "type",
      "Target": "xpath=//*[@id=\"instagram-link\"]//input[@placeholder=\"add profile name\"]",
      "Value": "txtInstagramProfileName",
      "Description": ""
    },
    {
      "Command": "pause",
      "Target": "1000",
      "Value": "",
      "Description": ""
    },
    {
      "Command": "click",
      "Target": "xpath=//*[@id=\"save-button\"]",
      "Value": "",
      "Description": ""
    },
    {
      "Command": "if_v2",
      "Target": "!${!statusOK} == true",
      "Value": "",
      "Description": ""
    },
    {
      "Command": "store",
      "Target": "2",
      "Value": "status",
      "Description": ""
    },
    {
      "Command": "store",
      "Target": "Cannot register chanel",
      "Value": "errorMessage",
      "Description": ""
    },
    {
      "Command": "gotoLabel",
      "Target": "THROW_EXCEPTION",
      "Value": "",
      "Description": ""
    },
    {
      "Command": "store",
      "Target": "none",
      "Value": "addressChanel",
      "Description": ""
    },
    {
      "Command": "else",
      "Target": "2",
      "Value": "",
      "Description": ""
    },
    {
      "Command": "pause",
      "Target": "3000",
      "Value": "",
      "Description": ""
    },
    {
      "Command": "store",
      "Target": "${!URL}",
      "Value": "addressChanel",
      "Description": ""
    },
    {
      "Command": "store",
      "Target": "1",
      "Value": "status",
      "Description": ""
    },
    {
      "Command": "store",
      "Target": "register chanel sucess",
      "Value": "errorMessage",
      "Description": ""
    },
    {
      "Command": "end",
      "Target": "",
      "Value": "",
      "Description": ""
    },
    {
      "Command": "end",
      "Target": "",
      "Value": "",
      "Description": ""
    },
    {
      "Command": "end",
      "Target": "",
      "Value": "",
      "Description": ""
    },
    {
      "Command": "label",
      "Target": "THROW_EXCEPTION",
      "Value": "",
      "Description": ""
    },
    {
      "Command": "if_v2",
      "Target": "${status} != -1",
      "Value": "",
      "Description": ""
    },
    {
      "Command": "pause",
      "Target": "3000",
      "Value": "",
      "Description": ""
    },
    {
      "Command": "executeScript_Sandbox",
      "Target": "var xhttp = new XMLHttpRequest();\n  xhttp.open(\"GET\", \"http://${DomainIp}:${DomainPort}/AccountExecute/UpdateAccountRunning?id=\" + ${recordId} + \"&status=\"+ ${status} + \"&message=\" + ${errorMessage}+ \"&actionStatus=\" + ${actionStatus} + \"&videoId=\" + ${txtVideoId} , true);\n  xhttp.send();",
      "Value": "",
      "Description": ""
    },
    {
      "Command": "end",
      "Target": "",
      "Value": "",
      "Description": ""
    },
    {
      "Command": "deleteAllCookies",
      "Target": "",
      "Value": "",
      "Description": ""
    },
    {
      "Command": "pause",
      "Target": "2000",
      "Value": "",
      "Description": ""
    },
    {
      "Command": "pause",
      "Target": "2000",
      "Value": "",
      "Description": ""
    },
    {
      "Command": "selectWindow",
      "Target": "TAB=CLOSEALLOTHER",
      "Value": "",
      "Description": ""
    },
    {
      "Command": "XType",
      "Target": "${KEY_CTRL+KEY_W}",
      "Value": "",
      "Description": ""
    }
  ]
}
