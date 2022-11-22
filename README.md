# noc_syosetu-fanyi.baidu


# noc_syosetu是啥


日文
成人版的成為小說家吧
（日語：小説家になろう／しょうせつかになろう)
	
# 主要思路

	* 將連載小說的章節連結全爬下來  herf
	
	* for迴圈連結爬小說
	
		
		+ ---->japan_list
		
	* 每 40行 為一組 丟入翻譯			
	
		+ ---->japan_list_spilt_merge
		
	* 用Selenium開啟fanyi.baidu
	
	* 記得關掉fanyi.baidu的廣告
	
	* 丟進去翻譯，強迫sleep 7 秒
	
	
		* ---->中文翻譯_list
		
	* 預設會在''C:\\Users\\user\\Desktop\\JYPUTER_試做\\' + org_name
	
	* 載入手機，用輕鬆讀小說打開
	
	* 也可用白樺閱讀打開
	
	* 可以手動將 print 出來的翻譯合成一個txt檔
	
# 主要問題	

* 如何更簡單的get翻譯

* 還是不會TXT檔的分章節

* 百度翻譯偶爾會失效，網頁不給翻譯，所以會丟失40行劇情




