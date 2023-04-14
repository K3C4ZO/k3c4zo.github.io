# C++ 基礎題

題目皆來自[zerojudge](https://zerojudge.tw)

## d049
[d049](https://zerojudge.tw/ShowProblem?problemid=d049)

```cpp
#include <iostream>
using namespace std;

int main()
{
	int y; //宣告儲存西元年的變數
	cin>>y; //讀入西元年
	cout<<y-1911<<endl; //輸出西元年-1911的值

	return 0;
}
```

## d050
[d050](https://zerojudge.tw/ShowProblem?problemid=d050)

```cpp
#include <iostream>
using namespace std;

int main()
{
	int h;
	cin>>h;
	if (h>=15) //若台灣時間>=15(美國時間與台灣同天)直接減時差就好了
		cout<<h-15<<endl;
	else //其他情況(美國時間是台灣的前一天)則要減時差後再加一天的時間
		cout<<h-15+24<<endl;


	return 0;
}


