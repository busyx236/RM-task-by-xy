//输出字符菱形
#include<iostream>
using namespace std;
int main()
{
	cout << "  *  \n *** \n*****\n *** \n  *  ";

	return 0;
}

//字符三角形
#include<iostream>
#include<string>
using namespace std;
int main()
{
	string a;
	int times=0;
	int n = 3;
	int line = 0;
	cin >> a;
	for (; n > 0; n--)
	{
		int x = n - 1;
		line++;
		for (; x > 0; x--) {
			cout << " ";
		}
		times = line * 2 - 1;
		for (;  times > 0; times--)
		{
			cout << a;
		}cout << "\n";
	}
	return 0;
}

//A+B proble
#include<iostream>
using namespace std;
int main()
{
	int a = 0;
	int b = 0;
	cin >> a >> b;
	cout << a + b;

	return 0;
}

//再分肥宅水
#include<iostream>
#include<iomanip>
using namespace std;
int main()
{
	float t = 0;
	int n = 0;
	cin >> t >> n;
	cout << fixed << setprecision(3) << t / n << endl << n * 2;
	return 0;
}

//上学迟到
#include<iostream>
#include<cmath>
using namespace std;
int main()
{
	int s = 0;
	int v = 0;
	cin >> s >> v;
	float sum = ceil(static_cast<float>(s) / v +10);
	int time = 8 * 60 - sum;
	if (time <= 0) {
		time += 24 * 60;
	}int hour = time / 60;
	int minute = time % 60;
	if (hour < 10) {
		cout << "0" << hour << ":";
	}
	else { cout << hour<<":"; }
	if (minute < 10) {
		cout << "0" << minute;
	}
	else { cout << minute; }
	return 0;
}

//闰年判断
#include<iostream>
using namespace std;
int main()
{
	int y = 0;
	cin >> y;
	if ((1582 <= y)&&(y <= 2020)) {
	}
	else { return 0; }
	if (y % 400 == 0 || (y % 4 == 0 && y % 100 != 0)) {
		cout << 1;
	}
	else {
		cout << 0;
	}
	return 0;
}

//三角形分类
#include<iostream>
using namespace std;
int a, b, c,t;
int main()
{
	cin >> a >> b >> c;
	if (a >= b && a >= c) {
		t = c;
		c = a;
		a = t;
	}
	else if (b >= a && b >= c) {
		t = c;
		c = b;
		b = t;
	}

	if (a + b <=c) {
		cout << "Not triangle";
		return 0;
	}
		if (a*a +b* b == c*c) {
			cout << "Right triangle"<<endl;	
		}
		if (a * a + b * b > c * c) {
			cout << "Acute triangle"<<endl;
		}
		if (a * a + b * b < c * c) {
			cout << "Obtuse triangle"<<endl;
		}
        if (a==b) {
			cout << "Isosceles triangle"<<endl;
		}
	if (a ==b&&b == c) {
		cout << "Equilateral triangle";
	}
	return 0;
}

//Apples
#include<iostream>
using namespace std;
int main()
{
	int x = 0;
	cin >> x;
	cout << "Today, I ate "<<x<<" apple";
	if (x > 1) {
		cout << "s";
	}cout << ".";
	return 0;
}

//
#include<iostream>
using namespace std;
int lc, lg;
int main()
{
	int n=0;
	cin >> n;
	lc = n * 5;
	lg = n * 3 + 11;
	if (lc < lg) {
		cout << "Local";
	}
	else {
		cout << "Luogu";
	}
	return 0;
}

//P1055
#include<iostream>
#include<string>
using namespace std;
int main()
{
	string IBSN;
	cin >> IBSN;
	int sum = 0;
	int n = 0;
	int code = 0;
	for (int i = 0; i < 11; i++) {
		if (IBSN[i] == '-') {
			continue;
		}n++;
		sum += (IBSN[i] - '0') * n;
		
	}code = sum % 11;
	if (code == 10 && IBSN[12] == 'X') {
		cout << "Right";
	}
	else if (code == 10 && IBSN[12] != 'X') {
		cout << IBSN.substr(0, 12) << "X";
	}
	else if (code != 10 && IBSN[12] - '0' == code) {
		cout << "Right";
	}
	else if (code != 10 && IBSN[12] - '0' != code) {
		cout << IBSN.substr(0,12)<<code;
	}
	return 0;
}
