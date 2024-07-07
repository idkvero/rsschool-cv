# Veronika Emelyanchenko

## **Contacts**
* **Location:** Minsk
* **Phone:** +375 29 37-35-322
* **Email:** v.emelyanchenko@gmail.com
* **GitHub:** idkvero
* **Discord:** idkvero

## **About me**
I'm just starting my journey in the frontend. I am currently taking courses from EPAM.

## **Skills**
* C++ basic
* Git

## **Code Examle**
```
#include <iostream>
using namespace std;


int main()
{
	double arr[100];
	int size;
	cout << "enter size ";
	cin >> size;


	cout << "enter elements" << endl;
	for (int i = 0; i < size; i++)
	{
		cin >> arr[i];
	}
	
	cout << "elements: ";
	for (int i = 0; i < size; i++)
	{
		cout << arr[i] <<  " ";

	}
	for (int i = 0; i < size-1; i++)
	{
		
		if (arr[i] > 0 && arr[i + 1] < 0)
		{
			for (int j = i; j < size-1; j++)
			{
				arr[j] = arr[j+1];
			}
			size--;
		
		}
	}

	cout << endl;
	for (int i = 0; i < size; i++)
	{
		cout << arr[i] << " ";
	}

	return 0;
}
```

## **Education**
**University:** Belarusian State University of Informatics and Radioelectronics
**Faculty:** Faculty of Information Technology and Control
**Specialty:** Automated information processing systems

## **English**
A2. I practiced English at school and now as a student