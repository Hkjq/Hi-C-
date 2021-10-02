#include<iostream>
using namespace std;

int main() {
	//伪随机 需要加入随机数种子
	srand((unsigned int)time(NULL));

	int num = rand() % 100 + 1;
	cout << num << endl;
	int sc = 0;
	while (sc != num) {
		cout << "猜数字" << endl;
		cin >> sc;
		if (sc == num)
		{
			cout << "猜对了" << endl;
			break;
		}
		else if (sc > num) {
			cout << "猜大了" << endl;
		}
		else {
			cout << "猜小了" << endl;
		}
	}


	system("pause");
	return 0;
}
