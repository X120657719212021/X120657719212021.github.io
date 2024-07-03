# X120657719212021.github.io
#joker園地



![1624190167259](https://github.com/X120657719212021/X120657719212021.github.io/assets/174402496/64d69c69-aa34-43f9-bbc1-938f70dc3999)

揚揚大江，先欲尋偶，慾望無望，倏舟而揚

![images](https://github.com/X120657719212021/X120657719212021.github.io/assets/174402496/ece9aeab-242c-4e30-8926-0bf59106519f)
product=["大腸麵線","大腸包小腸","蚵仔煎","牛肉麵","鹽酥雞"]
comment=[5.5,4.5,3.0,4.0,5.0]
for level in range(5):
    if  comment[level] > 5.0:
        print(product[level],"好吃")
    if comment[level] >4.0:
        print(product[level],"普通")
    else:
        print(product[level],"難吃")  
menu=input("請輸入菜名")
if product[3]:
    print(comment[3])  
