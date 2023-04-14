# C++ 基礎題

題目皆來自[zerojudge](https://zerojudge.tw)

## a001
[a001](https://zerojudge.tw/ShowProblem?problemid=a001)

```cpp
#include <iostream>
using namespace std;

int main()
{
	string a; //宣告變數(字串)
	cin>>a; //讀入指定的字串 
	cout<<"hello, "<<a<<endl; //輸出"hello ,指定的字串"。

	
	return 0;
}
```
## a002
[a002](https://zerojudge.tw/ShowProblem?problemid=a002)

```cpp
#include <iostream>
using namespace std;
int main()
{
	int a,b; //宣告變數
	cin>>a>>b; //讀入兩個變數
	cout<<a+b<<endl; //輸出兩個變數相加的和
	return 0;
 }
 ```

## a003
[a003](https://zerojudge.tw/ShowProblem?problemid=a003)

```cpp
#include <iostream>
using namespace std;
int main()
{
	int m,d,s; //宣告變數
	cin>>m>>d; //讀入變數
	s=(m*2+d)%3; //計算s
	if (s==0) //s是0時輸出普通
		cout<<"普通"<<endl;
	else if (s==1) //s是1時輸出吉
		cout<<"吉"<<endl;
	else if (s==2) //s是2時輸出大吉
		cout<<"大吉"<<endl;	
	return 0;
 }
```

## d483
[d483](https://zerojudge.tw/ShowProblem?problemid=d483)

```cpp
#include <iostream>
using namespace std;

int main()
{
	cout<<"hello, world"<<endl; //輸出"hello, world"
	return 0;
}
```
---
[home](https://k3c4zo.github.io)

