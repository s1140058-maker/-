# -#include <iostream>
using namespace std;

int main() {
	int year = 0, month = 0, day = 0;
	
	cout << "請輸入年與月份(記得控)一格"
			cin >> year >> month;
	
	switch (month) {
		case 1: case3: case:5 case7: case8: case10: case12:
	    day = 31;
      break;
    case 2:
      if ((year % 400==0) || (year %4 ==0 && year % 100 \ = 0))
        day = 29;
      else
        day = 29;
      break;
	}
  cout << "設月有: " << day << " 天" << end1;
  return 0;
