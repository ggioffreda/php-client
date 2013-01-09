Recognize.im API
===============

Recognize.im is providing API for Image Recognition. Those module is sample PHP connector to the API

Installation
============

Just download RecognizeImAPI.php and insert you credentials into config.php

Usage
=====
    // include class
    require("RecognizeImAPI.php");
	// and just call API methods
	$res = RecognizeImAPI::recognize(file_get_contents('test.jpg'));
	$imageList = RecognizeImAPI::imageList(); 

Authorization
=============

You don't need to call method auth by yourself. Module object will authorize you when needed, you just need do provide valid credentials. You can get them from your [account tab](http://recognize.im/user/profile)