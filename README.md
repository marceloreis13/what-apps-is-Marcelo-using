# What apps is Marcelo Reis using

here is some information about the setup I'm currently using.

## Terminal
* I use [iTerm2](https://www.iterm2.com/) instead of the stock terminal Mac app
* I use [oh-my-zshell](https://github.com/robbyrussell/oh-my-zsh)
* I use [Solarized Dark](http://ethanschoonover.com/solarized) for the terminal colors
* I use the [Meslo Powerline Font](https://github.com/powerline/fonts/blob/master/Meslo%20Slashed/Meslo%20LG%20M%20Regular%20for%20Powerline.ttf) as you need a font that supports the directory characters for `powerline` (click in View Raw to download)
* The results:

![term](term.png)

## Proxy
* I use [mitmproxy](https://mitmproxy.org/) An interactive console program that allows traffic flows to be intercepted, inspected, modified and replayed.

## Xcode
* I use [asset catalog creator](https://itunes.apple.com/br/app/asset-catalog-creator-free/id866571115?l=en&mt=12) for take images and create a full set of icons
* I use [Swift-Clean](http://www.swiftcleanapp.com/) to help me set a standard for writing clean Swift.
* I use [SwiftFormat](https://github.com/nicklockwood/SwiftFormat) for reformatting Swift code

## Menssegers
* [Slack](https://itunes.apple.com/br/app/slack/id803453959?l=en&mt=12) to brings all my communication together in one place.
* [Telegram](https://itunes.apple.com/br/app/telegram-desktop/id946399090?l=en&mt=12) because i'm not a end user =)


## Git Aliases
Some useful Git aliases to optimise your time!


<br />
**Add them with git config --global alias.{{your shortcut}} "{{git command}}"**

* a = "**a**dd ."
	
	```
	git config --global alias.a "add ."
	```

* alias = "! git config --get-regexp ^**alias**\. | sed -e s/^alias\.// -e s/\ /\ =\ /"

	```
	git config --global alias.alias "! git config --get-regexp ^alias\. | sed -e s/^alias\.// -e s/\ /\ =\ /"
	```

* arane = "commit --**a**mend --**r**eset-**a**uthor --**n**o-**e**dit"

	```
	git config --global alias.arane "commit --amend --reset-author --no-edit"
	```


* ca = "**c**ommit --**a**mend"

	```
	git config --global alias.ca "commit --amend"
	```

* cane = "**c**ommit --**a**mend --**n**o-**e**dit"
	
	```
	git config --global alias.cane "commit --amend --no-edit"
	```



* cc = "**c**he**c**kout"

	```
	git config --global alias.cc "checkout"
	```

* ck = "**c**hec**k**out"

	```
	git config --global alias.ck "checkout"
	```

* ckd = "**c**hec**k**out **d**ev"

	```
	git config --global alias.ckd "checkout dev"
	```

* ckm = "**c**hec**k**out **m**aster"

	```
	git config --global alias.ckm "checkout master"
	```


* cm = "**c**ommit -**m**"

	```
	git config --global alias.cm "commit -m"
	```

* co = "**co**mmit"

	```
	git config --global alias.co "commit"
	```

* cp = "**c**herry-**p**ick"
	
	```
	git config --global alias.cp "cherry-pick"
	```
	
* dom = "**d**iff --stat **o**rigin/**m**aster"

	```
	git config --global alias.dom "diff --stat origin/master"
	```

* ft = "**f**etch --**t**ags"

	```
	git fetch --tags
	```
	
* fod = "**f**etch **o**rigin **m**dev:dev"

	```
	git config --global alias.fod "fetch origin dev:dev"
	```

* fom = "**f**etch **o**rigin **m**aster:master"
	
	```
	git config --global alias.fom "fetch origin master:master"
	```


* fu = "add . && git commit --amend --no-edit && git push -**f** origin master"

	```
	git config --global alias.fu "add . && git commit --amend --no-edit && git push -f origin master"
	```

* logi = "**log** --pretty=onel**i**ne"

	```
	git config --global alias.logi "log --pretty=oneline"
	```

* md = "**m**erge **d**ev"

	```
	git config --global alias.md "merge dev"
	```

* mm = "**m**erge **m**aster"
	
	```
	git config --global alias.mm "merge master"
	```

* pod = "**p**ush **o**rigin **d**ev"
	
	```
	git config --global alias.pod "push origin dev"
	```

* pfo = "**p**ush -**f** **o**rigin"
	
	```
	git config --global alias.pfo "push -f origin"
	```
	
* pfod = "**p**ush -**f** **o**rigin **d**ev"
	
	```
	git config --global alias.pfom "push -f origin dev"
	```

* pfom = "**p**ush -**f** **o**rigin **m**aster"
	
	```
	git config --global alias.pfom "push -f origin master"
	```

* po = "**p**ush **o**rigin"

	```
	git config --global alias.po "push origin"
	```

* pom = "**p**ush **o**rigin **m**aster"
	
	```
	git config --global alias.pom "push origin master"
	```
* pomt = "**p**ush **o**rigin **m**aster --**t**ags"

	```
	git push origin master --tags
	```

* puo = "**pu**ll **o**rigin"
	
	```
	git config --global alias.puo "pull origin"
	```


* puom = "**pu**ll **o**rigin **m**aster"
	
	```
	git config --global alias.puom "pull origin master"
	```
p

* rao = "**r**emote **a**dd **o**rigin"

	```
	git config --global alias.rao "remote add origin"
	```

Feel free to fork and PR! 🚀
