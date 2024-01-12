# thesaurus

Kemdict 同義詞/異義詞資料未來的家

- 重編本還是簡編本有提供同義詞/異義詞資料，Kemdict還需要整合
- iTaigi也是華↔台同義詞字典
- 除了這些之外，教育部字典的同義詞/異義詞資料不夠；我也希望有更多華↔英和華↔日同義詞資料
- 我認為我可能可以想辦法做些什麼

資料會用純文字儲存，方便合併。

- type (= for synonym, ! for antonym)
- from (word) + lang
- to (word) + lang

word language could be specified elsewhere, in the file name or something.

We also need an editing interface, either in Emacs, as a local web app, or as a hosted web app. The interface should have a mode to choose a random word from the database and allow data entry.
