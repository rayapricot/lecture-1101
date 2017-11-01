# テクノロジー（藤原） 11/1授業

```
rayapricot:~/workspace $ git clone git@github.com:rayapricot/lecture-1101.git
Cloning into 'lecture-1101'...
Warning: Permanently added 'github.com,192.30.253.113' (RSA) to the list of known hosts.
remote: Counting objects: 3, done.
remote: Compressing objects: 100% (2/2), done.
remote: Total 3 (delta 0), reused 3 (delta 0), pack-reused 0
Receiving objects: 100% (3/3), done.
rayapricot:~/workspace $ pry
[1] pry(main)> num = 2
=> 2
[2] pry(main)> if num % 2 == 0
[2] pry(main)*   puts "偶数です。"
[2] pry(main)* end  
偶数です。
=> nil
[3] pry(main)> puts "偶数です。" if num % 2 == 0
偶数です。
=> nil
[4] pry(main)> num = rand 3
=> 0
[5] pry(main)> num
=> 0
[6] pry(main)> num
=> 0
[7] pry(main)> num
=> 0
[8] pry(main)> num
=> 0
[9] pry(main)> num
=> 0
[10] pry(main)> num
=> 0
[11] pry(main)> num
=> 0
[12] pry(main)> rand 3
=> 0
[13] pry(main)> rand 3
=> 2
[14] pry(main)> rand 3
=> 1
[15] pry(main)> rand 3
=> 0
[16] pry(main)> rand 3
=> 2
[17] pry(main)> rand 3
=> 2
[18] pry(main)> rand 3
=> 1
[19] pry(main)> rand 3
=> 0
[20] pry(main)> rand 3
=> 2
[21] pry(main)> rand 3
=> 1
[22] pry(main)> num 1000
NoMethodError: undefined method `num' for main:Object
from (pry):24:in `__pry__'
[23] pry(main)> num = 1000
=> 1000
[24] pry(main)> if num >= 1500
[24] pry(main)*   puts "送料無料"
[24] pry(main)* elsif 0 < num && num < 1500  
[24] pry(main)*   puts "送料300円"
[24] pry(main)* else  
[24] pry(main)*   puts "入力が間違っていま[24] pry(main)*   puts "入力が間違っていま[24] pry(main)* end  
送料300円
=> nil
[25] pry(main)> 1000
=> 1000
[26] pry(main)> num 1500
NoMethodError: undefined method `num' for main:Object
from (pry):34:in `__pry__'
[27] pry(main)> def triangle(b, h)
[27] pry(main)*   result = b*h / 2.0
[27] pry(main)*   result #返り値は最後の一[27] pry(main)*   result #返り値は最後の一[27] pry(main)* end  
=> :triangle
[28] pry(main)> triangle(11, 9)
=> 49.5
[29] pry(main)> triangle 11, 9            
=> 49.5
[30] pry(main)> name = gets
ichi
=> "ichi\n"
[31] pry(main)> name
=> "ichi\n"
[32] pry(main)> name.chomp!
=> "ichi"
[33] pry(main)> name
=> "ichi"
[34] pry(main)> 10 times do |i|
SyntaxError: unexpected tIDENTIFIER, expecting end-of-input
10 times do |i|
        ^
[34] pry(main)> 10 times do |i|
SyntaxError: unexpected tIDENTIFIER, expecting end-of-input
10 times do |i|
        ^
[34] pry(main)> print i
NameError: undefined local variable or method `i' for main:Object
from (pry):45:in `__pry__'
[35] pry(main)> 10 times {|i| print i, ", "}
SyntaxError: unexpected tIDENTIFIER, expecting end-of-input
10 times {|i| print i, ", "}
        ^
[35] pry(main)> a = ["りんご","みかん","ぶ[35] pry(main)> a = ["りんご","みかん","ぶ=> ["りんご",
 "みかん",
 "ぶどう"]
[36] pry(main)> a.each do |item|
[36] pry(main)*   puts "おいしい" + item + "だよ"
[36] pry(main)* end  
おいしいりんごだよ
おいしいみかんだよ
おいしいぶどうだよ
=> ["りんご",
 "みかん",
 "ぶどう"]
[37] pry(main)> 
```