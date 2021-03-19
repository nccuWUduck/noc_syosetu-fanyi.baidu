# noc_syosetu-fanyi.baidu

#noc_syosetu是啥
	+日文 成人版的成為小說家吧（日語：小説家になろう／しょうせつかになろう)
	
#主要思路
	+將連載小說的章節連結全爬下來  herf
	+for迴圈連結爬小說
		+短篇小說直接爬 
		+---->japan_list
	+資料清洗
		+---->japan_list_clear
	+每5000個日文字分割			
		+---->切5000字_list
	+用Selenium開啟fanyi.baidu
	+記得關掉fanyi.baidu的廣告
	+丟進去翻譯，強迫sleep 7 秒
	+每430個 切5000字 寫出一次
		+---->中文翻譯_list
	+預設會在'C:\\Users\\user\\Desktop\\ero_novel\\'+ org_name
	+載入手機，用輕鬆讀小說打開
	
#主要問題	
##如何更簡單的get翻譯
##還是不會TXT檔的分頁



