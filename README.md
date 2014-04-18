idx
===

Index files with pre-sorted data in key-value pairs (KVPs)

### FORMATS ###

+ `txt` - colon-delimited, similar to Java properties files
+ `json` - Unicode-escaped JavaScript Object Notation 


### IDX LIST ###

+ `IdxHanyuPinyin`
  + KVPs of Chinese characters and Hanyu Pinyin pronunciation

+ `IdxPinyinPhonemes`
  + KVPs of Hanyu Pinyin phoneme keys, where all values equal 1
  
+ `IdxSimplified`
  + KVPs of Traditional Chinese and Simplified Chinese
  
+ `IdxToneMarks`
  + KVPs of pinyin tone numbers and tone marks
  + ordered by string length, descending
  
+ `IdxToneNumbers`
  + KVPs of pinyin tone marks and tone numbers
  + ordered by string length, descending
