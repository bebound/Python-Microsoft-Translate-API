Python-Microsoft-Translate-API
==============================

Microsoft(Bing) translate API for python3


----------

###Requirement

[Requests](http://docs.python-requests.org/en/latest/)

[Python3](https://www.python.org/downloads/)

----------

###Installation

	pip install mstranslate

----------

###Usage

	from mstranslate import MSTranslate

	kk = MSTranslate('client_id', 'client_secret')
	print(kk.translate('你好', 'en'))
	>>> How do you do
PS:You can specificy the from language as the third parameter in translate() function.
