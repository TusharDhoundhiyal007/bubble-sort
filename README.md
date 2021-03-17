#include<iostream>
using namespace std;

int main()
{
	int i=0,n ,arr[10];
	// input the number of elements in an aray
	cin>>n;
	
	// enter the elements in an array
	for(int i=0;i<n;i++){
		cin >>arr[i];
	}
	for(int i=0;i<n-1;i++){
		for(int j=0;j<n-1;j++){
			if(arr[j]>arr[j+1]){
				swap(arr[j],arr[j+1]);
			}
		}
	}
		for(int i=0;i<n;i++){
		cout <<arr[i];
}
}
