# Başlangıç Seviye Java ile Backend Web Development Patikası

# Veri yapıları ve algoritmalar dersi 
---

# Binary Search Tree projesi 


## CEVAP AŞAMALARI
Öncelikle burada 7'yi root olarak seçtim. (İnternet üzerinde var olan bir örneği baz aldım, aksi halde lineer bir dağılım sergilenecekti.)

7'yi root olarak seçtikten sonraki ilk oluşum şu şekilde oldu:

                    7
                   /\
                  5  8

Elemanlar seçilirken kümedeki sıralama kıyasıya önem arz etmektedir. Genel kural olarak, bir node'un solunda olması gereken sayı bahsedilen node'un sayısal değerinden küçük olmalıdır, ve keza sağındaki de büyük olmalıdır.

Bahsedilen kurallara göre yapılan sıralamanın tamamı şöyle resmedilebilir:


                    7
                   /\
                  5  8
                 / \   \
                3   6   9
               /
              1
             /\
            0  2


