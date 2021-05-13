# testing-repository
- NitroType Garage-Space Hack is made by @AtomiicCoder, and was originally made by @Ray-Adams.
- Changelog
-  5/12/2021 10:19 PM - Changed the two prompts and started working on other script inside repository.
--------------------------------------------COPY AND PASTE BELOW INTO A BOOKMARK AND OPEN IT WHEN YOUR IN THE NITROTYPE GARAGE-----------------------------------------------------
- javascript:(async(a,b=prompt`: How many garage spaces would you like? You must re-organize your garage before trying this again. [Each garage space can hold 30 cars!]:`,c='',d)=>{for(d=0;d<b*30;d++)c+=`garage%5B${d}%5D=&`;await fetch('https://www.nitrotype.com/api/cars-arrange',{'headers':{'Content-Type':'application/x-www-form-urlencoded'},'body':c+a,'method':'POST','mode':'cors'});alert`Logging out of account, log back in. [This method is not bannable, and mods approve of this!]`;await fetch('https://www.nitrotype.com/api/logout',{'headers':{'Content-Type':'application/x-www-form-urlencoded'},'body':a,'method':'POST','mode':'cors'});location.reload()})(`uhash=${encodeURI(document.cookie.match`(^|;) *ntuserrem=([^;]*)`[2])}`)
